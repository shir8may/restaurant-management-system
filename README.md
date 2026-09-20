# 🍽 Restaurant Management System

A client-server restaurant management system developed as a six-member team project as part of a Software Engineering course.

The system supports multiple restaurant branches and includes functionality for reservations, deliveries, menus, customer services, role-based access, and operational reporting.

## 🛠 Technologies

- Java
- JavaFX
- MySQL
- OCSF
- Maven
- Client-Server Architecture

## 👩‍💻 My Contributions

- Developed reporting functionality for operational reports, including delivery orders, rejected reservations, and customer complaints.
- Designed JavaFX user interfaces across multiple system features and user roles.
- Created UML and Use Case diagrams and contributed to requirements documentation and system design throughout the project.

## 🏗 Project Structure

The project consists of three main modules:

1. **client** – JavaFX client application using OCSF.
2. **server** – Server-side application using OCSF.
3. **entities** – Shared module containing the project's entities.

## ▶️ Running the Project

1. Run Maven install in the parent project.
2. Run the server using the `exec:java` goal in the server module.
3. Run the client using the `javafx:run` goal in the client module.
