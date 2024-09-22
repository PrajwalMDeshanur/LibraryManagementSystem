# Library Management System Database

## Project Overview
This project involves the design and implementation of a relational database system for managing the operations of a library. It tracks the inventory of books, borrowing and returning activities, and subscriber information, ensuring efficient data management and retrieval.

## Objective
To create a robust and normalized database system that simplifies library operations, maintains data integrity, and minimizes redundancy.

## Database Design
- **Normalization**: The database is structured to follow the Third Normal Form (3NF), which ensures that data is logically stored and reduces redundancy.
- **Entities**: Includes key entities such as `Books`, `Authors`, `Subscribers`, `Book Copies`, `Categories`, and `Publishers`.
- **Relationships**: Captures the relationships between books and authors, subscribers and borrowed books, and books and categories.

## Key Features
- **Book and Author Management**: Stores detailed information about each book and its authors.
- **Subscriber Management**: Keeps track of subscriber details and their borrowing history.
- **Borrowing System**: Manages the issuance and return of books to subscribers.
- **Category Organization**: Classifies books into various categories for better organization.
- **Publisher Information**: Maintains records of book publishers and their contact details.

## Implementation
- **Schema Design**: Created tables and established relationships between them using SQL commands.
- **SQL Commands**: Implemented necessary constraints to ensure data consistency and integrity.
- **Queries**: Generated 35 optimized SQL queries for common library operations such as:
  - Viewing borrowing history of subscribers.
  - Listing most borrowed books.
  - Tracking overdue returns.

## Outcome
- The database system provides a structured and scalable solution for managing library operations.
- Ensures efficient data retrieval and reporting, supporting day-to-day library functions with ease.
- Maintains high data integrity and consistency, reducing potential errors in data management.

## How to Use
1. **Setup**: Use the provided SQL file (`Library.sql`) to create the database schema in your preferred database management system (e.g., MySQL, PostgreSQL).
2. **Data Insertion**: Populate the tables with sample data to simulate library operations.
3. **Query Execution**: Run the provided SQL queries to perform various operations like tracking book borrowings, finding popular books, and managing subscriber data.

## Conclusion
This project demonstrates the effective use of database design principles to manage the complex operations of a library. The system is optimized for performance, data integrity, and scalability, making it a reliable solution for library management.

---
