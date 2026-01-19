# SQLProjectEmployeeManagementSystem

## 📌 Project Overview
This project is a **SQL-based Employee Management System** designed to handle core HR data operations. It simulates a real-world database environment where structural changes, data integrity checks, and business logic updates are required. 

The project involves creating a relational schema for **Departments** and **Employees**, populating it with sample data, and executing complex schema alterations to adapt to changing business requirements.

## 🛠️ Tech Stack
- **Database:** MySQL
- **Language:** SQL (DDL, DML, DQL)
- **Tools:** MySQL Workbench / Command Line

## 📂 Database Schema
The system consists of two primary relational tables:

1. **Departments Table**
   - `DepartmentID`: Unique identifier (Primary Key)
   - `DepartmentName`: Name of the department (e.g., HR, IT)
   - `Location`: Physical location of the department
   - `HeadOfDepartment`: Name of the department head
   - `AnnualBudget`: Allocated budget for the department

2. **Employees Table**
   - `EmployeeID`: Unique identifier (Primary Key)
   - `FirstName` & `LastName`: Employee details
   - `DepartmentID`: Foreign key linking to the Departments table
   - `Salary`: Employee's annual salary
   - `DateOfJoining`: Hire date
   - `Email`: Unique contact email

## 🚀 Key Features & Scenarios Handled
This project solves **10 specific business situations**, demonstrating the following SQL capabilities:

- **Database Initialization**: Creating databases and tables with appropriate data types and constraints (`NOT NULL`, `UNIQUE`, `PRIMARY KEY`, `AUTO_INCREMENT`).
- **Data Integrity**: Enforcing relationships using **Foreign Keys**.
- **Schema Evolution**:
  - Adding new columns (e.g., adding a `Status` column with a default value of 'Active').
  - Renaming columns to reflect organizational restructuring (e.g., renaming `DepartmentID` to `TeamID`).
- **Business Constraints**:
  - Managing data consistency during updates.
  - Partitioning strategies for archiving old data (e.g., separating employees who joined before 2020).

## 💻 How to Use
1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/your-username/Employee-Management-SQL.git](https://github.com/your-username/Employee-Management-SQL.git)
