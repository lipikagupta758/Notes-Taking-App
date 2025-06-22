

# Java Project with Spring MVC: Note-Taking App

## Introduction
This project is a note-taking application developed using Java with Spring MVC framework. It allows users to create, read, update, and delete notes. The application follows the MVC (Model-View-Controller) architectural pattern to ensure a separation of concerns and maintainability.

## Prerequisites
- JDK (Java Development Kit) installed on your system
- Apache Maven for building and managing dependencies
- MySQL or any other relational database management system

## Installation and Setup
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/lipikagupta758/Notes-Taking-App.git
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Configure the database:
    - Create a PostgreSQL database named `notesDB2`.
    - Update the `application.properties` file in `src/main/resources` directory with your database credentials.

4. Build the project using Maven:
    ```bash
    mvn clean install
    ```

## Running the Application
1. After successfully building the project, run the application using Maven:
    ```bash
    mvn spring-boot:run
    ```
2. Once the application is running, access it through your web browser:
    ```
    http://localhost:4041
    ```

## Features
- **Create Note:** Users can create new notes by providing a title and content.
- **Read Note:** Users can view existing notes along with their titles and content.
- **Update Note:** Users can edit the content of existing notes.
- **Delete Note:** Users can delete notes they no longer need.

## Technologies Used
- Java
- Spring MVC
- Thymeleaf (for server-side HTML rendering)
- MySQL (or any other relational database)
- Maven
