# Real Estate Management System (REMS)

## Overview

The Real Estate Management System (REMS) is a comprehensive solution designed to manage various aspects of real estate properties, including rental shops, apartments, branches, and occupant administration. The system is built using C# and SQL Server, providing a robust and scalable platform for real estate management.

## Features

-   **Rental Shops Management**: Manage rental shops, including filtering by region, city, contractor, and status.
-   **Apartments Management**: Manage apartments with filtering options for region, city, number of bedrooms, and status.
-   **Branches Management**: View and filter branches by region, city, and branch type.
-   **Occupant Administration**: Manage occupant information with options to add, edit, delete, and search occupants.
-   **Account Management**: Add new user accounts with details such as username, password, first name, last name, branch ID, and user type.

## Installation

1. **Clone the repository**:
    ```bash
    https://github.com/million-mesfin/Real-Estate-Management-System.git
    ```
2. **Open the solution**:
   Open the `REMS.sln` file in Visual Studio.

3. **Restore NuGet packages**:
   In Visual Studio, go to `Tools` > `NuGet Package Manager` > `Package Manager Console` and run:

    ```powershell
    Update-Package -reinstall
    ```

4. **Setup the database**:

    - Create a new database in SQL Server.
    - Run the SQL scripts provided in the `Database` folder to create the necessary tables and seed data.

5. **Configure the connection string**:
    - Open `appsettings.json` or `Web.config` (depending on your project type).
    - Update the connection string to point to your SQL Server instance and database.

## Usage

1. **Run the application**:
   Press `F5` in Visual Studio to build and run the application.

2. **Login**:
   Use the provided credentials to log in to the system.

3. **Navigate through the system**:
    - Use the side navigation to access different modules such as Rental Shops, Apartments, Branches, and Occupant Administration.
    - Utilize the filtering options to narrow down the data as per your requirements.

## Contributing

We welcome contributions to enhance the functionality and features of REMS. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your fork.
4. Create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
