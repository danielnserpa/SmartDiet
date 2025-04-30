# Diet Smart App

Diet Smart is a simple, user-friendly app designed to help users manage their diet plans. The application allows users to register, log in, and receive personalized diet plans, all based on the expertise of nutritionists.

## Features

- **User Registration**: Users can sign up by providing their email, first name, last name, and password.
- **User Login**: Registered users can log in using their email and password.
- **Diet Plan**: Upon login, users can access a ready-to-follow diet plan, which is personalized for them.
- **Password Reset**: If a user forgets their password, they can request a reset.

## Technologies Used

- **Spring Boot**: The backend framework for the application.
- **Spring Data JPA**: For data persistence.
- **Thymeleaf**: For rendering dynamic HTML views.
- **HTML/CSS**: For basic frontend styling and layout.
- **JavaScript**: For handling form logic (e.g., storing email in local storage, password validation).

## Prerequisites

Ensure the following are installed on your system:

- **Java 8+**
- **Maven** (for building the project)
- **IDE** (such as IntelliJ IDEA, Eclipse, or VS Code)

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/diet-smart-app.git

2. **Navigate to the Project Directory**
```bash
cd diet-smart-app
```

3. **Build the Project
```bash
mvn clean instal
```

4. **Run the Application**
```bash
mvn spring-boot:run
```

After running the application, you can access it at http://localhost:8080.

## Pages and Routes

- **Home Page (`/`)**: The landing page with a general description of the app and the option to log in or register.

- **Login Page (`/login`)**: Page where users can log in with their credentials.

- **Register Page (`/register`)**: Page for new users to register with their details.

- **Diet Plan Page (`/dashboard`)**: After logging in, users are redirected to their dashboard where they can view their personalized diet plan.

## User Flow

1. **Visit Home Page**: Users can read about the app and click the "Log In" or "Register" button.

2. **Register**: Users enter their email, name, and password to create an account.

3. **Log In**: Users enter their credentials (email and password) to log in.

4. **Dashboard**: After login, users are directed to a page with their personalized diet plan, made by professional nutritionists.


