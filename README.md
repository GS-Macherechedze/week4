# Week  4

This week, you'll delve into entity-relationship modelling (ERM) by designing an ERD for a library management system. You'll focus on representing the relationships between books, authors, library members, and borrowings.

## Learning Objectives:

By the end of this week, you'll be able to:

Identify entities and their attributes relevant to a library system.
Understand the concept of relationships (cardinalities) between entities.
Design an ERD using appropriate symbols to represent entities, attributes, and relationships.
Address many-to-many relationships using associative entities.

___________________________________________________________________________________________________________
## Instructions (Read and follow instructions)

1. Answer all questions (text, diagrams etc.) in one Microsoft Word document.
2. Ensure your SQL statements are well-formatted and include comments to explain their purpose.
3. Upload your document on this repo.
4. Share this GitHub repo as your LMS submission link 
___________________________________________________________________________________________________________

Suppose you're tasked with designing an Entity Relationship Diagram (ERD) for a basic library system. The system needs to track information about books, authors, library members, and borrowing history. Design an ERD to represent these relationships.

## Requirements:
Entities:
Book: Each book has a unique ID, title, and publication year. Author: Each author has a unique ID and name. Library Member: Each member has a unique ID and name. Borrowing: Each borrowing has a unique ID, a due date, and a return date.

## Relationships:
Each book can have one or more authors, and each author can write one or more books. Each borrowing is associated with one book and one library member. A book can be borrowed by multiple members, and a member can borrow multiple books.

## Tasks:
Design an ERD:
Create an ERD illustrating the relationships between books, authors, library members, and borrowings. Use simple symbols to represent entities, attributes, and relationships.

**Implement the Schema:**
Using SQL, implement the database schema you designed. Ensure appropriate data types, constraints, and relationships (foreign keys) are defined for each table.

**Populate the Database:**
Populate each table with sample data. Ensure that there are enough records to demonstrate the relationships between entities.
