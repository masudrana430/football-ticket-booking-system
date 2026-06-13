# Football Ticket Booking System

## Project Overview

This project is a simplified Football Ticket Booking System database design assignment. It includes database schema design, ERD relationships, sample data insertion, and SQL queries using filtering, pattern matching, null handling, joins, subqueries, aggregation, and pagination.

## Tables

### Users
Stores all football fans and ticket managers.

### Matches
Stores tournament match information, ticket prices, and match ticket status.

### Bookings
Stores individual ticket booking transactions by connecting users with matches.

## Relationships

- One User can have many Bookings.
- One Match can have many Bookings.
- Each Booking belongs to exactly one User and one Match.
- Each Booking represents one reserved seating choice.

## Technologies Used

- PostgreSQL
- SQL
- Draw.io / Lucidchart for ERD

## Files

- `QUERY.sql`: Contains table creation, sample data insertion, and required assignment queries.
- `ERD_LINK.txt`: Contains the public ERD link.
- `screenshots/`: Contains query output screenshots.

## How to Run

1. Open PostgreSQL or pgAdmin.
2. Create a new database.
3. Open the `QUERY.sql` file.
4. Run the full script.
5. Check each query output.