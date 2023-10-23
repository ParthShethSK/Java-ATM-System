# Java ATM System

Welcome to the Java ATM System repository. This project is a fully functional ATM application with a graphical user interface. Users can log in, register new accounts, check their account balance, deposit funds, withdraw money, and safely log out.

## Features

- User-friendly graphical interface.
- Secure login and registration.
- Real-time account balance updates.
- Connection to an MS Access database for data storage.
- Multiple operations, including balance check, deposit, and withdrawal.

## Prerequisites

Before you can run this project, you need to set up the required development environment and configure the database connection. Follow these steps:

1. **Java Development Kit (JDK):** Make sure you have Java Development Kit (JDK) installed on your system. If not, download and install it from [Oracle's official website](https://www.oracle.com/java/technologies/javase-downloads.html).

2. **NetBeans IDE:** This project was developed using NetBeans. You can download NetBeans IDE from the [official website](https://netbeans.apache.org/download/index.html).

3. **MS Access Database Setup:**
   - Open your Windows Start menu.
   - Navigate to "Settings" > "Control Panel" > "Administrative Tools."
   - Double-click on "Data Sources (ODBC)."
   - In the "System DSN" tab, click "Add..."
   - Choose "Microsoft Access Driver (*.mdb)" if available. If not, select the appropriate driver for your MS Access version.
   - Give your data source a name (e.g., "ATMINFO").
   - Click "Select" and navigate to your project folder to select the provided "ATMINFO.mdb" file.
   - Click "OK" to save the Data Source Name.

## Running the Application

Follow these steps to run the Java ATM System:

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/ParthShethSK/Java-ATM-System.git
   
2. Open the project in NetBeans.

3. Build and run the project

   - **Build the Project:**
     - In NetBeans, right-click on the project name (Java-ATM-System) in the "Projects" panel on the left.
     - Select "Build" from the context menu. This action compiles the project.

   - **Run the Project:**
     - After building the project, right-click on the project name (Java-ATM-System) again in the "Projects" panel.
     - Select "Run" from the context menu. This will start the application.

4. The ATM System application will open, allowing you to log in or register a new account.

# Project Structure
The project structure consists of the following key files:

- `ATMSystem.java` - The main application entry point.
- `Login.java` - Handles user login and registration.
- `Registration.java` - Manages user registration.
- `Transaction.java` - Supports transactions such as balance check, deposit, and withdrawal.

## Contributing
If you'd like to contribute to this project, feel free to submit pull requests or open issues on the repository.

Enjoy using the Java ATM System!


