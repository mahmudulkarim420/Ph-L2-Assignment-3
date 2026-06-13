# Football Ticket Booking System

## Overview

This project is a simple Football Ticket Booking System database designed using PostgreSQL. It demonstrates database design concepts, ERD relationships, primary and foreign keys, data integrity, and SQL query operations.

## Database Structure

The system consists of three tables:

### Users

Stores information about football fans and ticket managers.

### Matches

Stores football match details, tournament categories, ticket prices, and match status.

### Bookings

Stores ticket booking records by connecting users and matches.

## Entity Relationship Diagram (ERD)

### Relationships

* One User can have Many Bookings.
* One Match can have Many Bookings.
* Each Booking belongs to exactly one User and one Match.

## Features

* Primary Key and Foreign Key relationships
* Data validation using CHECK constraints
* NULL handling using COALESCE
* Pattern matching using LIKE and ILIKE
* INNER JOIN and LEFT JOIN operations
* Subqueries and aggregate functions
* Sorting and pagination using ORDER BY, LIMIT, and OFFSET

## Files Included

* `QUERY.sql` – Table creation, sample data, and SQL queries
* `ERD.png` – Entity Relationship Diagram
* `Theory_Answers.md` – Theory question answers

## Technologies Used

* PostgreSQL
* Draw.io / Mermaid ERD

## Author

Mahmudul Karim
