# Final Year Project - Cinema Ticket Booking System
The Cinema Ticket Booking System is divided into two different systems that talk to
each other and communicate via a database. There is a desktop application that is
only used by the Cinema Owners and Admins, and a web-based system that is
accessible to Customers and Guests that want to book tickets and reserve seats for a
particular movie, at a given time and date. The desktop application is written in Java
using the JavaFX library, and the web-based system is implemented in C# using the
ASP.NET framework, and a Microsoft SQL Server database is used by both systems
so they can send and retrieve data to communicate with each other. The Cinema
Owners have the ability to add, view, and delete Admins, view any movie that exists
in the database regardless of its status (archived, playing now, or coming soon),
search for a movie in the system and view its details, bookings, and trailer. Admins
are also able to browse movies depending on their status, with the main difference
being that only Admins can add, edit, or remove a movie from the system. They can
also view all the bookings made for a movie and its trailer, but more importantly, they
can delete a booking, if requested. Customers can create an account and view the
playing now or coming soon movies only, since the archived ones are of no concern
to them. They can view a movie’s details and trailer, and can then proceed to book a
ticket and reserve seat(s) for a particular date and time. After entering the information
requested, they receive an email confirmation that contains the ticket details (movie
poster and title, reserved seat(s), ticket holder name etc.). This functionality is also
available for Guests (customers without registering an account), but they do not have
the ability to change their reserved seats, movie date and show time, or cancel the
booking, unlike logged in customers. Cinema Owners, Admins, and registered
Customers have the ability to update their account details, reset their password, login,
and logout etc. Data validation and attention to detail are vital and key components of
this project to ensure that the software can be used as intended, with minimal to no
errors. Duplicate usernames, weak passwords, alphabetic characters in phone
numbers, incorrect email formatting, future date of birth, reserve already booked seats,
book a ticket for a date and time that has passed etc. are *not* allowed. By studying
already-established movie theatre systems and being inspired by online streaming
services, the Cinema Ticket Booking System mimics the behaviour and functionality
of such systems in order to provide a pleasant and smooth customer experience, and
be accessible and usable to people without prior experience in using such systems.
