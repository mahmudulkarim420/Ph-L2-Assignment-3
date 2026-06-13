# Theory Answers

## Question 1: What role does a Foreign Key play in the Bookings table?

A Foreign Key creates a relationship between tables. In the Bookings table, `user_id` references the Users table and `match_id` references the Matches table. It helps maintain data integrity by ensuring that a booking cannot be created for a user or match that does not exist.

---

## Question 4: If a newly registered fan has not bought any match tickets yet, what will a LEFT JOIN return?

A LEFT JOIN returns all records from the left table and matching records from the right table. If a fan has not purchased any tickets, the user's information will still appear in the result, while the booking-related columns will contain NULL values.

---

## Question 5: What is the difference between a main query and a subquery?

A main query is the primary query that returns the final result. A subquery is a query written inside another query. Subqueries are useful when the result of one query is needed by another query, such as comparing values with an average or filtering specific records.
