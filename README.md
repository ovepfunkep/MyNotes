# MyNotes
Project Task: Task Management Application
Overview:
Develop a Task Management Application where users can create, manage, and track their tasks. The application should support user authentication, task categorization, and real-time notifications for task updates using RabbitMQ.

Requirements:
User Authentication:

Implement user registration and login functionalities.
Use JWT (JSON Web Tokens) for secure user sessions.
Task Management:

Users should be able to create, read, update, and delete tasks.
Each task should have attributes such as title, description, status (pending, in-progress, completed), and due date.
Implement task categorization (e.g., work, personal, urgent).
Microservices Architecture:

Break the application into microservices:
User Service: Manages user information and authentication.
Task Service: Handles all task-related operations.
Each microservice should be a separate project using ASP.NET Core with Entity Framework for data access.
Database:

Use PostgreSQL for data storage.
Ensure proper schema design for users and tasks.
Message Queue:

Implement RabbitMQ for real-time notifications when tasks are created or updated.
Notify users when they have been assigned a task or when a task’s status changes.
Frontend Development:

Use React for building the frontend.
Implement an intuitive and responsive user interface for task management.
Use Redux for state management.
Testing:

Write unit tests for all services using NUnit.
Ensure high test coverage for critical functionalities.
Containerization:

Use Docker to containerize your application.
Provide a docker-compose file to spin up the necessary services (User Service, Task Service, PostgreSQL, and RabbitMQ).
Documentation:

Write comprehensive README.md documentation on how to run the application, including Docker setup and API documentation.
Include diagrams of the microservices architecture.
Deployment:

Optionally, deploy your application on a cloud platform (e.g., AWS, Azure, or Heroku) and provide the link in your README.
Deliverables:
A GitHub repository containing your code.
A well-structured project with clear commit messages and documentation.
A working instance of your application (if deployed).
