🚗 Vehicle Rental System – Database Design & SQL Queries

A complete assignment submission covering ERD design, table structure, sample queries, and viva preparation.

📌 Overview

This project demonstrates database design skills using a Vehicle Rental System.
It includes ERD creation, SQL query writing, and theory explanations.

The system manages three core entities:

Users

Vehicles

Bookings

🎯 Objectives

By completing this assignment, you will be able to:

Design an ERD with One-to-One, One-to-Many, and Many-to-One relationships

Understand Primary Keys (PK) and Foreign Keys (FK)

Write SQL queries using:

JOIN

EXISTS

WHERE

GROUP BY & HAVING

🧩 Part 1 — ERD (Entity Relationship Diagram)

The ERD must clearly represent:

Tables

Users

Vehicles

Bookings

Relationship Requirements

One to Many: One user can have many bookings

Many to One: Many bookings belong to one vehicle

Logical One to One: Each booking references one user and one vehicle

Attributes to Include

Primary keys

Foreign keys

Status fields (vehicle availability, booking status)

Relationship cardinality

📌 The ERD must be created using Lucidchart and submitted as a public share link.

🛢️ Part 2 — SQL Queries

You must write queries based on your designed schema.

Required Queries

JOIN Query
Retrieve booking information along with customer name and vehicle name.

EXISTS Query
Find all vehicles that have never been booked.

WHERE Query
Retrieve all available vehicles of a specific type (e.g., cars).

GROUP BY + HAVING Query
Show total number of bookings per vehicle, only for vehicles with more than 2 bookings.

🧪 What Your Database Should Handle
Users Table Must Store

User role (Admin/Customer)

Name, email, password, phone

Unique email

Vehicles Table Must Store

Vehicle name, type (car/bike/truck), model

Unique registration number

Price per day

Availability status (available, rented, maintenance)

Bookings Table Must Store

User who booked

Vehicle booked

Start & end dates

Booking status (pending/confirmed/completed/cancelled)

Total cost

🎤 Part 3 — Viva / Theory Questions

Answer these questions in your own words in a 2-minute video:

1. What is a foreign key and why is it important?

Explain how it maintains relationships and referential integrity.

2. Difference between WHERE and HAVING in SQL.

Describe when filtering happens before or after grouping.

3. What is a primary key?

Explain uniqueness, non-null, and identification of records.

4. Difference between INNER JOIN and LEFT JOIN.

Explain matching behavior and non-matching rows.