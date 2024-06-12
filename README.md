# SUST Medical Center Management System

## Project Overview
The SUST Medical Center Management System is a web-based application designed to automate and streamline the operations of the SUST Medical Center. This system will computerize patient demography maintenance, prescription management, medicine distribution, and stock maintenance, reducing the reliance on manual and paper-based processes.

## Major Functions
- Computerization of the existing manual management system.
- Maintenance of patient diagnosis details and advised tests.
- Management of patient prescriptions, medications, instructions, precautions, and diet advice.
- Record-keeping and maintenance of medicine stock through central-store and sub-store.
- Tracking newly purchased medicines and monitoring their usage.
- Generation of billing reports for employee patients.
- Proposal of a list of medicines to be purchased in the upcoming month.
- Password recovery through a hint question.

## Users
1. **General User (Patient):** Students and Staff.
2. **Administrative User:** Doctors, Pharmacists, Store Officers, and Medicine Distributors.

## System Interfaces
- **Client on Internet:** Web Browser, Operating System (any).
- **Client on Intranet:** Client Software, Web Browser, Operating System (any).
- **Web Server:** Apache Tomcat, Operating System (any).
- **Database:** MySQL.

## User Interface
Graphical user interfaces (GUI) will be provided for all users. These GUIs can be both web-based and desktop-based, connected to the medical central terminal. The interfaces are designed to be simple and user-friendly.

## Communication Interface
- **Client on Internet:** HTTP/HTTPS Protocol.
- **Client on Intranet:** TCP/IP Protocol.

## Requirements
1. JDK 6u1 (or higher)
2. NetBeans IDE 6.9.1 (or higher)
3. MySQL Database:
   - mysql-5.1.39
   - mysql-connector-odbc-5.1.6
   - mysql-gui-tools-5.0-r17
4. mysql-connector-java-5.1.6-bin.jar
5. Apache Tomcat 6.0.26 (integrated with NetBeans)
6. Firefox 3.6.3 (or higher)

## Installation Instructions
1. **Install JDK:**
   - Download and install the JDK.
2. **Install NetBeans IDE:**
   - Download and install NetBeans IDE (Version 6.9.1).
3. **Install MySQL:**
   - Install MySQL and its components (mysql-5.1.39, mysql-connector-odbc-5.1.6, mysql-gui-tools-5.0-r17).
   - Default username: `root`, password: `admin`.
   - If you want to change the username and password, modify the `database.java` file located at `project\MedicalCentre\src\java\medicalcenter`.
4. **Install Firefox:**
   - Download and install Firefox (Version 3.6.3 or higher).
5. **Import Project in NetBeans:**
   - Open NetBeans IDE.
   - Import the `MedicalCentre` project as a web project.
   - Add `mysql-connector-java-5.1.6-bin.jar` to Libraries if not already added.

## Known Issues
- You may encounter database-related issues even after proper installation and configuration.
- Refer to the `DBQuery.sql` file for database queries (triggers, procedures, events, etc.).

## Dummy Users
Several dummy users are available in the system for testing purposes:

| User Name  | Password  | User Type         |
|------------|-----------|-------------------|
| doctor     | d         | Doctor            |
| doctor2    | d         | Doctor            |
| pharmacist | p         | Pharmacist        |
| md         | md1       | Medicine Distributor |
| a-cse      | p         | Patient (Employee) |
| b-cse      | p         | Patient (Employee) |
| 2007331039 | mokarrom  | Patient (Student) |
| 2007331023 | p         | Patient (Student) |

## Technical Documentation
A detailed technical report explaining the different phases (e.g., requirement analysis, system design, architecture, coding, debugging, and testing) of the software engineering process is available in the `docs` directory.

