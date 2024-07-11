# Kitchen Story Project Documentation

## Overview

The **Kitchen Story** project is a web application developed using React for the frontend and Spring Boot for the backend. It allows users to view food items, search for items, and provides an admin dashboard for managing food items.

- **GitHub Repository:** [Kitchen Story Repository](https://github.com/fr-ananya/kitchen-story)

## Project Structure

The project is structured into two main components:

1. **Frontend (React)**:
   - Located in the `frontend` directory.
   - Implements user-facing components, including home page, search functionality, and admin dashboard.
   - Utilizes React Router for navigation and Axios for HTTP requests to the backend.

2. **Backend (Spring Boot)**:
   - Located in the `backend` directory.
   - Provides RESTful APIs for retrieving and managing food items.
   - Uses Spring Data JPA for data persistence and MySQL database for storage.

## Frontend (React)

### Directory Structure

- `public/`: Contains index.html and other static assets.
- `src/`: Contains React components, CSS files, and utility functions.
  - `components/`: Individual UI components such as Navbar, Home, AdminDashboard.
  - `App.js`: Main application component.
  - `index.js`: Entry point for React application.
  - `axios.js`: Axios configuration for API requests.
  - `Home.css`: Styling specific to the home page.

### Setup Instructions

1. Clone the repository: `git clone https://github.com/fr-ananya/kitchen-story.git`
2. Navigate to the `frontend` directory: `cd frontend`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Open `http://localhost:3000` in your browser to view the application.

## Backend (Spring Boot)

### Directory Structure

- `src/main/java/`: Contains Java classes for the backend application.
  - `com.project.controller/`: REST controllers for handling API requests.
  - `com.project.model/`: Entity classes representing data models.
  - `com.project.repository/`: Spring Data repositories for database operations.
  - `com.project.service/`: Business logic and service classes.
  - `com.project.kitchen/`: Main application class and configuration.
- `src/main/resources/`: Contains application properties and SQL scripts.

### Setup Instructions

1. Ensure MySQL is installed and running.
2. Configure database credentials in `application.properties`.
3. Run the Spring Boot application from your IDE or using Maven: `mvn spring-boot:run`.
4. The application will start on `http://localhost:8080`.

## Database

- **MySQL Database**:
  - The backend uses MySQL database for storing food items.
  - Configuration details are specified in `application.properties`.

## Additional Notes

- **Technologies Used**:
  - Frontend: React, React Router, Axios
  - Backend: Spring Boot, Spring Data JPA, MySQL
  - Version Control: Git, GitHub

- **Contributors**: Ananya Yaya

## Conclusion

The **Kitchen Story** project demonstrates the integration of React frontend with a Spring Boot backend to create a responsive web application for managing food items. For more details, refer to the GitHub repository linked above.
