# Finance Management System

The Finance Management System is a web application developed using ReactJS and Spring Boot to assist individuals and businesses in managing their finances effectively. It provides tools for budget management, expense tracking, and spending analysis.

## Features

- **Budget Management:** Create, edit, and track multiple budgets. Set budget limits and monitor spending against these limits.
  
- **Expense Tracking and Recording:** Log daily expenses, categorize them, and maintain a historical record of transactions.
  
- **Spending Analysis:** Visualize spending patterns through interactive charts and graphs. Gain insights into spending habits.

## Technologies Used

### Frontend

- **React.js:** A JavaScript library for building user interfaces, ensuring a dynamic and responsive user experience.
- **Material-UI:** A popular React UI framework for implementing Google's Material Design, providing modern and customizable UI components.
- **Chart.js:** A flexible JavaScript charting library that allows for the creation of interactive and animated charts, integrated with React through `react-chartjs-2`.

### Backend

- **Spring Boot:** A powerful, production-ready, and easy-to-use framework for creating stand-alone, production-grade Spring-based applications.
- **MySQL:** An open-source relational database management system used for storing and managing the application’s data.
- **RESTful APIs:** Implemented to handle the communication between the frontend and backend, enabling smooth data exchange and interaction.

### Documentation

This project includes extensive documentation to help understand the system's design and implementation:
- **Architectural Diagrams:** Visual representations of the system's architecture.
- **Class Diagrams:** Depictions of the system's classes and their relationships.
- **Domain Models:** Models showing the domain entities and their interactions.
- **System Sequence Diagrams:** Diagrams detailing the sequence of operations within the system.
- **System Diagrams:** High-level subsystem and interconnections.
- **Use Cases:** Descriptions of the system's functionalities from an end-user perspective.

## Motivation

The project aims to provide a user-friendly tool for effective financial management, inspired by the need for efficient personal and business finance solutions.

## Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js and npm:** Install from [Node.js official website](https://nodejs.org/). To verify the installation, run the following commands in your terminal: ``node -v`` and ``npm -v``.
- **Java Development Kit (JDK):** Ensure Java 8 or higher is installed. Download from [Oracle's JDK download page](https://www.oracle.com/java/technologies/javase-downloads.html).
- **Eclipse IDE for Enterprise Java and Web Developers:** Install from [Eclipse official website](https://www.eclipse.org/downloads/packages/).
- **MySQL:** It's recommended to use MySQL Workbench for easier database management. Download it from [MySQL Workbench download page](https://dev.mysql.com/downloads/workbench/).
- **VS Code:** Download from [VS Code official website](https://code.visualstudio.com/).

## Installation

### Clone the Repository
Clone this repository to your local machine using Git:

```
git clone https://github.com/NoorUlBaseer/Finance-Management-System
```
### Backend Setup

1. **Open Eclipse IDE:**
   - Launch `Eclipse IDE for Enterprise Java and Web Developers`.

2. **Import Project:**
   - Select `File` > `Open Projects from File System...`.
   - In the dialog box, click the `Directory` button and browse to the cloned repository folder.
   - Select the folder named `SpringBoot` and click `Select Folder`.

3. **Project in Workspace:**
   - The backend project will now appear in the `Workspace` (Package Explorer) on the left side of Eclipse.

4. **Update Maven Project:**
   - Right-click the opened project in the `Workspace`.
   - Select `Maven` > `Update Project...`.

5. **Update Database Configurations:**
   - Open the `application.properties` file located in `src/main/resources`.
   - Update the database configurations as per your local MySQL setup:
        `spring.datasource.url=jdbc:mysql://localhost:3306/[your-database-name]`

        `spring.datasource.username=[your-username]`

        `spring.datasource.password=[your-password]`

6. **Run Backend Application:**
   - Navigate to the main `Application.java` file in the `src/main/java` directory.
   - Right-click on the `Application.java` file.
   - Select `Run As` > `Java Application`.

7. **Access Backend:**
   - The backend will start and run on port `9000`.
   - Verify the backend is running by checking the Eclipse console for logs indicating: `Tomcat started on port 9000` and `Started Application in [specific-seconds] seconds`.

#### Note:
- Ensure MySQL server is running and accessible with the credentials provided in `application.properties` file.

### Frontend Setup

1. **Open VS Code:**
   - Launch `Visual Studio Code`.

2. **Open Cloned Repository:**
   - Click on `File` > `Open Folder...`.
   - Browse to the directory where you cloned the repository and select it to open in VS Code.

3. **Open Terminal in VS Code:**
   - Once the repository is open, open a terminal within VS Code by navigating to `Terminal` > `New Terminal`.

4. **Install Dependencies:**
   - Ensure the terminal in VS Code is open at the directory of the cloned repository.
   - Run the following command to install the necessary dependencies:
     `npm install`

5. **Install Material-UI and Chart.js:**
   - Ensure the terminal in VS Code is open at the directory of the cloned repository.
   - Run the following commands to install Material-UI and Chart.js:
        `npm install @mui/material @emotion/react @emotion/styled`

        `npm install chart.js`

        `npm install react-chartjs-2`

        `npm install chartjs-plugin-datalabels`
   - Ensure all commands are completely executed and everything is installed on your system.

6. **Start the Frontend Application:**
   - In the terminal, run the following command to start the development server:
    `npm start`

7. **Access Frontend:**
   - The frontend application will start, and you can access it by opening a web browser and navigating to `http://localhost:3000`.

#### Note:
- Ensure there are no errors in the terminal during the setup.
