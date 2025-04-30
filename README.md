# Diet Smart App

Diet Smart is a simple, user-friendly app designed to help users manage their diet plans. The application allows users to register, log in, and receive personalized diet plans, all based on the expertise of nutritionists.

## Features

- **User Registration**: Users can sign up by providing their email, first name, last name, and password.
   
- **User Login**: Registered users can log in using their email and password.

- **Diet Plan**: Upon login, users can access a ready-to-follow diet plan, which is personalized for them by professional nutritionists.

- **Password Reset**: If a user forgets their password, they can request a password reset.

- **Health Metrics**: Users can track various health metrics on their dashboard, including:
   - Daily calorie intake
   - Macronutrient breakdown (carbs, proteins, fats)
   - Recommended daily water intake
   - Progress tracking for weight loss or muscle gain

## Technologies Used

- **Spring Boot**: The backend framework for the application.
- **Spring Data JPA/MySQL**: For data persistence.
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

3. **Build the Project
   ```bash
   mvn clean instal

4. **Run the Application**
   ```bash
   mvn spring-boot:run

After running the application, you can access it at http://localhost:8080.

## Pages and Routes

- **Home Page (`/`)**: The landing page with a general description of the app and the option to log in or register.

- **Login Page (`/login`)**: Page where users can log in with their credentials.

- **Register Page (`/register`)**: Page for new users to register with their details.

- **Diet Plan Page (`/dashboard`)**: After logging in, users are redirected to their dashboard where they can view their personalized diet plan.

## User Flow

1. **Visit Home Page**: Users can read about the app and click the "Log In" or "Register" button.

2. **Register**: Users enter their email, name, and password to create an account.

3. **Log In**: Registered users enter their credentials (email and password) to log in.

4. **Complete Profile**: Upon first login, users are prompted to complete their profile by entering personal details such as age, weight, height, and fitness goals.

5. **Dashboard**: After completing their profile, users are directed to their dashboard, where they can view their personalized diet plan, made by professional nutritionists based on the information provided.

## 🙋 Author
Made by Daniel Nascimento

