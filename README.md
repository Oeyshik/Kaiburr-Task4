
# Kaiburr Task 4: WEB UI Frontend

This project is the frontend part of Kaiburr Task 4, created using Angular. It complements the REST API developed using Spring Boot (Kaiburr Task 1) by providing a user-friendly web interface to interact with the server data.


## Table of Contents

- [Project Structure](#project-structure)
- [How the Task Is Made](#how-the-task-is-made)
- [Requirements](#requirements)
- [Prerequisites](#prerequisites)
- [How to Run the Application](#how-to-run-the-application)
- [Screenshots](#screenshots)
## How the Task Is Made

The task consists of creating a web-based frontend using Angular that interacts with a REST API implemented using Spring Boot. The frontend provides functionality to view a list of servers, create new servers, edit existing servers, and delete servers.

The application uses Angular components to separate different parts of the user interface:

- **Create Server Component**: Allows users to create a new server by providing server details.
- **Edit Server Component**: Provides a form for editing server details.
- **Server List Component**: Displays a list of servers, and users can edit or delete individual servers.

The frontend communicates with the backend using HTTP requests to perform CRUD (Create, Read, Update, Delete) operations on the server data.
## Project Structure
- `src/`: This directory contains the source code and resources for the project.
    - `app/`: The main application code.
        - `create-server/`: This directory contains the Create Server Component.
        - `edit-server/`: This directory contains the Edit Server Component.
        - `server/`: This directory contains the Server List Component.
        - `server.service.ts`: This TypeScript file is the Server Service.
        - `app.component.ts`: The main component of the Angular application.
        - `app.module.ts`: The main module of the Angular application.
        - `app.component.html`: The main HTML template for the Angular application.
        - `...`  Other Angular components and modules.
    -  `assets/`: This directory holds static assets like images.
        - `images/`: Subdirectory for image assets.
            - `logo.png`: The logo image used in the application.
- `...`  Other Angular configuration and setup files.


## Prerequisites
- Node.js and npm (Node Package Manager)
- Angular CLI
## Project Setup
Before running the application, make sure you have the following:

1. Node.js and npm installed. You can download them from [here](https://nodejs.org/).
2. Angular CLI installed globally. You can install it using npm:

   ```bash
   npm install -g @angular/cli

### How to Run the Application
Follow these steps to run the frontend of the Kaiburr Task 4:

1. Clone the repository to your local machine:

    ```bash
    git clone <repository-url>

2. Navigate to the project folder:

    ```bash
    cd kaiburr-task-4-frontend

3. Install the project dependencies:

    ```bash
    npm install

4. Start the Angular development server:

    ```bash
    ng serve

5. Open a web browser and access the application at 
    ```bash
    http://localhost:4200/.
## Screenshots
### Web UI FrontEnd
![App Screenshot](https://drive.google.com/uc?id=1bE8S9W42CYVpaFQoOw_9fsbDWQStdpZo)
