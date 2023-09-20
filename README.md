
# Kaiburr Task 4: WEB UI Frontend

This project is the frontend part of Kaiburr Task 4, created using Angular. It complements the REST API developed using Spring Boot (Kaiburr Task 1) by providing a user-friendly web interface to interact with the server data. This project showcases how to build a modern web application frontend using Angular, enhancing server management and administration.


## Table of Contents

- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [How the Task Is Made](#how-the-task-is-made)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Prerequisites](#prerequisites)
- [How to Run the Application](#how-to-run-the-application)
- [Screenshots](#screenshots)

## Key Features
- Create new servers with specific details.
- Edit server information, including name, language, and framework.
- Delete individual servers or all servers.
- View a list of servers with their details.
- Interactive user interface for seamless server management.

## Technologies Used
- Angular: A powerful and popular web application framework.
- TypeScript: A statically typed superset of JavaScript.
- Angular Material: A UI component library for Angular applications.
- Bootstrap 4: A responsive and customizable CSS framework.
- RESTful API: Communicates with the backend using RESTful web services.

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
![App Screenshot](https://drive.google.com/uc?id=1l5d8BKilb_wgCxMY2bhXuIpEATISeYYB)

### task1.servers: MongoDB Database Collection
![App Screenshot](https://drive.google.com/uc?id=13obnnzZdAP_bl7yYgV-2vPzphToi3Pp3)

### Create Server MatDialog
![App Screenshot](https://drive.google.com/uc?id=1qURsR_eMTeH7pFNSIqEHuIk-htLy-M5M)

### Create Server Inserting Data
![App Screenshot](https://drive.google.com/uc?id=10ymorwGRMTHrfQwY0Qi1VvXq0NCVt4Gg)

### Create Server Succesfull Message
![App Screenshot](https://drive.google.com/uc?id=1VsS8rj0TdUQ2kg_X3wUePjqnXCuWbxg6)

### Web UI FrontEnd after Creating a Server
![App Screenshot](https://drive.google.com/uc?id=1-EUJEVLClhfIlzOa6YlZUcCstAXO4vR1)

### task1.servers: MongoDB Database Collection after Creating a Server
![App Screenshot](https://drive.google.com/uc?id=1zT0WHDNpOAH_ZgK7KnS1SYH69ZkhR4I9)

### Server Creation is reflected in http://localhost:8080/api/servers
![App Screenshot](https://drive.google.com/uc?id=1as89U_2PyR-4dHAS-9MgkHsAXRTZgCJS)

### Server Creation is reflected in http://localhost:8080/api/servers
![App Screenshot](https://drive.google.com/uc?id=1as89U_2PyR-4dHAS-9MgkHsAXRTZgCJS)

### Web UI FrontEnd after Creating multiple servers
![App Screenshot](https://drive.google.com/uc?id=1-M40XfmVfNrFOUUywYRqZeb3BF02NrYK)

### Edit Server MatDialog
![App Screenshot](https://drive.google.com/uc?id=1dN0H0Q9ll4Mxci8VgKGaWamrL2NJQA73)

### Updating Server Details
![App Screenshot](https://drive.google.com/uc?id=1FZnaqpMnWlDHsCLMEuaRbcaZYUFvBXdE)

### Edit Server is reflected in Web UI FrontEnd
![App Screenshot](https://drive.google.com/uc?id=1rCl081EWBJK6l1U8kPhsPvZlf8Jf3oyf)

### Edit Server is reflected in MongoDB
![App Screenshot](https://drive.google.com/uc?id=1rCl081EWBJK6l1U8kPhsPvZlf8Jf3oyf)

### Delete a Server Alert Message
![App Screenshot](https://drive.google.com/uc?id=1luaHTMH_KLAYMCBM4m78_qWFPmBBNI9P)

### Deleting a Server
![App Screenshot](https://drive.google.com/uc?id=1T1W5pkyxHv3J-T1wDaMMZbHnbGFWIqXe)

### task1.servers: MongoDB Database Collection
![App Screenshot](https://drive.google.com/uc?id=1BJ7DnJg_Aj-1rRheyh1RiDN12RCKZzMO)

### Delete All Servers Alert Message
![App Screenshot](https://drive.google.com/uc?id=1spwgVyqGsB1JJrDccIz-iAUGqy3igsJ1)

### task1.servers: MongoDB Database Collection after Deleting All Servers
![App Screenshot](https://drive.google.com/uc?id=1l5d8BKilb_wgCxMY2bhXuIpEATISeYYB)

### Web UI FrontEnd At End
![App Screenshot](https://drive.google.com/uc?id=13obnnzZdAP_bl7yYgV-2vPzphToi3Pp3)
