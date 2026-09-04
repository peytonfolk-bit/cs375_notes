**Data**: Sign/symbol to represent some object/information

**Database**: Collection of data

**Database Management System**: is a software system for creating, storing, managing and retrieving data in a structured way

# Database Management Systems

- Used for performing some particular tasks
- U of R uses Banner 
    - Stores student, course, instructor, and other things data
    - Allows us to retrieve this data
        - Maybe GPA, student ID, etc
    - Application Programming Interface (API)
        - API is the waiter at a restaurant that gets you your food
*Selection*
- Table/relation/entity: mean the same thing

Example Table:

| Name | Student id | Age | GPA |
|---|---|---|---|
| Jeff | 1000000 | 17 | 67% |
| Peyton | 200506776 | 20 | 100% |


- Each Student is a row

**This data is stored in a database management system, for us to retrive, process, collect, and maintain**

## Database Design:
*6 steps:*
1. Requirment Analysis
2. Conceptual Database Design (will do this)
3. Logical Database Design (will do this)
4. Schema Refinement (will do this)
5. Physical Database Design
6. Application and Security

## Data Analysis:
- Analyzing the data within a database

## Concurrency:
- We want 20,000 people to be able to work at the same time for example at the U of R
- People using the database here would be using UR Self-Service, UR Courses, etc

## Robustness:
- If something fails you have backup, system won't be changed or leaked
- Have to have permissions in place

## Efficiency:
- How quickly we can process changes

## Scalability:
- Systems ability to handle growing amounts of work, data, or user traffic efficiently

# Files vs DBMS: 
Why do we need database management system and not just files?

*Size*
- Let's say we have 500GBs of data
    - We do not have the RAM for that
    - Even if we did wouldn't work

*Different levels of permissions*
- Everyone should have different levels of permissions
- Student shouldn't have same as an instructor

*Inconsistent changes*
- Ensures consistency, some people might write a person name as their last name, while others would put the persons first name for example

*Restore at an appropriate state*
- Transaction management

*Different programs for different*
