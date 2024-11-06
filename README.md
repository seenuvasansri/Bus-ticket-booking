Bus Ticket Booking System
Overview
The Bus Ticket Booking System is a console-based application developed in Java that allows users to manage bus seat bookings. This system enables users to sign up, log in, book tickets, and cancel bookings for available buses. The system also supports gender-based seating restrictions where users are restricted from booking vertically adjacent seats with mismatched genders unless they are the same user.

This project simulates a basic bus ticket booking system with functionality for both users and administrators. Users can view available buses, check seat availability, book or cancel tickets, and view booking history. The system enforces gender compatibility rules for adjacent seat bookings, ensuring that users of different genders cannot sit next to each other in vertical rows unless explicitly allowed (i.e., if the same user makes the adjacent booking).

Features
User Authentication: Users can sign up, log in, and manage their bookings.
Bus Details: Displays a list of available buses with their fares.
Seat Availability: Shows a visual representation of available and booked seats.
Booking Functionality: Allows users to book seats based on available options and apply gender-based restrictions.
Cancellation: Users can cancel bookings if they are the original bookers.
Admin Summary: Admin can view the total income generated from all buses.
User Summary: Users can view their booking history and active reservations.
Key Restrictions
Gender Compatibility: Users cannot book vertically adjacent seats with different genders (unless they are the same user).
Seat Availability: Only available seats can be booked. Invalid or already booked seats are not available for selection.
Technologies Used
Java: The primary programming language used to implement the system.
Collections: Utilizes Java collections like Map, List, and Set for managing users, bookings, and buses.
