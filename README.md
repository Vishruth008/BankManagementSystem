
# Bank Management System (SWIFTBANK)

## Overview
The Bank Management System is a comprehensive solution to streamline banking operations, enhance customer experience, and efficiently manage transactions. This system focuses on optimizing ATM management and providing secure online banking services, supported by a robust database design.

## Features
- **Centralized Dashboard**: Provides real-time insights into banking activities, including transactions, account balances, and customer interactions.
- **ATM Management**: Tracks cash availability, ensures operational efficiency, and triggers alerts when ATMs need attention.
- **Online Banking Services**: Facilitates secure fund transfers, recurring payments, and account management with a user-friendly interface.
- **Database Design**: Includes Entity-Relationship Diagram (ERD) modeling, normalization, stored procedures, triggers, indexing, encryption, and user-defined functions.

## Project Modules
1. **Database Design and Implementation**
   - Conceptual modeling and ERD creation.
   - Database creation using DDL and DML statements.
   - Normalization for data consistency and efficiency.
2. **Stored Procedures and Views**
   - Creation of stored procedures for managing customer accounts, transactions, and beneficiaries.
   - Custom views for efficient data access.
3. **System Enhancements**
   - Addition of indexing, encryption, and user-defined functions.
   - Implementation of check constraints, triggers, and a GUI for CRUD operations.

## ERD Highlights
- **Generalization**: Combines mobile and online banking entities to form a generalized banking entity.
- **Specialization**: Defines separate transaction entities for ATM, online, mobile, and branch transactions.
- **Normalization**: Addresses data dependencies to ensure efficient organization and compliance with the third normal form.

## Getting Started
### Prerequisites
- **Database**: MySQL or a similar RDBMS.
- **Development Environment**: VSCode, SQL Client.
- **Dependencies**: Import relevant SQL scripts for database initialization.

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/Vishruth008/BankManagementSystem.git

   ```
2. Navigate to the project directory:
   ```
   cd bank-management-system
   ```
3. Set up the database using the provided SQL scripts:
   - Run `final_project_DML.sql` for database initialization.

### Running the Application
- Set up your RDBMS and load the database schema.
- Launch the GUI application for CRUD operations and perform banking transactions.

## Contributors
- Vishruth Telugu Venugopal
- Santhish Kumar Nagarajan
- Sai Krishna Reddy Gaddam
- Sai Abhishek Ila
- Riya Singh

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact vishruthtv30@gmail.com.
