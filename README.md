# Student-Library-Database-System
A comprehensive Library Database System built with SQL Server, featuring a relational schema (ERD) and 10 specialized T-SQL Stored Procedures for advanced reporting and borrowing management.
Project Overview
This project is a relational database system designed to manage library operations efficiently. It tracks books, authors, and student borrowings while ensuring data integrity through structured relationships and constraints.

🏗️ Database Architecture
The system is built on a normalized schema consisting of 6 primary tables:

Authors: Stores author profiles and contact information.

Categories: Classification of books (e.g., Science, History).

Books: Inventory details for all available titles.

Students: Management of library members and their details.

Borrowings: Transactional records for book loans and returns.

BookAuthors: A junction table facilitating the Many-to-Many relationship between authors and books.

🚀 Key Features & SQL Procedures
I have implemented 10 Stored Procedures to automate critical library reporting tasks:

Overdue Tracking: Identifies books not returned within the 14-day limit.

Student Activity: Calculates the total books borrowed per student.

Recent Borrowing Analysis: Tracks students who borrowed books last week but haven't returned them.

Inventory Stats: Counts books per author and per category.

Behavioral Insights: Identifies students borrowing the same book multiple times or across different categories.

🛠️ Tech Stack
RDBMS: Microsoft SQL Server

Language: T-SQL

Tool: SQL Server Management Studio (SSMS)

📷 Database Diagram


Author: Abdulrahman Hamza

Faculty: Faculty of Computer and Information Systems, Mansoura University
