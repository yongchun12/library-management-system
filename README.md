# Library Management System

A Windows Forms desktop application developed using **VB.NET** and **SQL Server** for managing basic library operations such as user login, book records, member information, and database-driven library data.

## Project Overview

This project was developed as an academic assignment to demonstrate desktop application development using VB.NET Windows Forms and relational database integration. The system focuses on supporting common library management tasks through a graphical user interface and structured database storage.

## Features

- User login interface
- Forgot password interface
- Library data management using SQL database
- Windows Forms-based graphical user interface
- Database script included for system setup
- Desktop application structure using Visual Studio solution and project files

## Tech Stack

- **Programming Language:** VB.NET
- **Framework:** .NET 6.0 Windows
- **Application Type:** Windows Forms Desktop Application
- **Database:** SQL Server
- **IDE:** Visual Studio

## Project Structure

```text
library-management-system-vbnet/
├── Admin Center/
├── My Project/
├── Resources/
├── ApplicationEvents.vb
├── Assignment_1.sln
├── Assignment_1.vbproj
├── Library_Management_System.sql
├── frmForgetPassword.vb
├── frmForgetPassword.Designer.vb
├── frmForgetPassword.resx
├── frmLogin.vb
├── frmLogin.Designer.vb
├── frmLogin.resx
└── README.md
```

## Database

The repository includes the SQL script:

```text
Library_Management_System.sql
```

This file can be used to create or restore the required database structure for the application.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yongchun12/library-management-system-vbnet.git
```

2. Open the solution file in Visual Studio:

```text
Assignment_1.sln
```

3. Restore or execute the database script:

```text
Library_Management_System.sql
```

4. Update the database connection string if required.

5. Build and run the project in Visual Studio.

## Screenshots

Screenshots can be added here to show the login page, admin dashboard, book management page, and other system interfaces.

```text
screenshots/
├── login-page.png
├── dashboard.png
└── book-management.png
```

## Future Improvements

- Add role-based access control for admin and staff users
- Improve password recovery and account security
- Add book borrowing and return tracking
- Add overdue book notification feature
- Improve user interface design
- Add reporting and export features

## Project Status

This project is completed as an academic assignment and can be further improved with additional library management features.

## Author

Developed by **Yong Chun**.
