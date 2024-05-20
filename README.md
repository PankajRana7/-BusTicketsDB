# -BusTicketsDB
Overview:

BusTicketsDB is a relational database designed to manage ticket bookings for a bus ticket booking website or application. It consists of three main tables: Customers, Buses, and Bookings. These tables store essential information related to customers, buses, and bookings, enabling efficient tracking and management of the ticket booking process.

Schema:

The schema definition for BusTicketsDB is provided in the schema.sql file. This file contains SQL statements to create the necessary tables, define primary and foreign keys to establish relationships between tables, and insert sample data for testing purposes.

Customers Table:

The Customers table stores information about customers who book tickets.
Fields include customer_id (primary key), customer_name, email, phone, and city.
Buses Table:

The Buses table contains details of available buses.
Fields include bus_id (primary key), bus_number, route, and seats.
Bookings Table:

The Bookings table tracks bookings made by customers.
Fields include booking_id (primary key), customer_id (foreign key referencing Customers table), bus_id (foreign key referencing Buses table), booking_date, seat_number, and price.
SQL Formulas Used:

BusTicketsDB utilizes various SQL formulas to interact with the database and extract valuable insights:

CREATE TABLE: To create tables in the database.
ALTER TABLE: To modify table structures (e.g., add constraints).
INSERT INTO: To insert data into the tables.
SELECT: To retrieve data from one or more tables.
GROUP BY: To group rows that share common attributes.
JOIN: To combine rows from two or more tables based on a related column.
ORDER BY: To sort the result set in ascending or descending order.
HAVING: To filter rows returned by a GROUP BY clause based on specified conditions.
Insights:

Analyzing the data in BusTicketsDB can provide valuable insights into the bus ticket booking process, including:

Booking Patterns: Identify peak booking times, popular routes, and preferred seat choices.
Customer Analysis: Understand customer demographics, booking behavior, and preferences.
Revenue Analysis: Calculate total revenue, average booking value, and revenue trends over time.
Route Optimization: Optimize bus routes based on booking demand and customer feedback.
Seat Utilization: Analyze seat occupancy rates to maximize bus capacity and revenue.


