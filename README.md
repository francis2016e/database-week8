# database-week8
Title of my project: clinic booking system

what my project does are listed below:

  patients Table
Stores patient details including name, date of birth, email, and phone number.

  Doctors Table
Holds information about doctors, including their contact details.

  Specializations Table
Maintains a list of medical specialties (e.g., Pediatrics, Cardiology).

  DoctorSpecializations Table
A many-to-many relationship between doctors and their specializations.

  Appointments Table
Tracks appointments between patients and doctors, including the date and reason.

  Payments Table
Handles payment information for each appointment, supporting cash, card, and insurance methods.

 Key Features:
Relational structure with foreign keys to ensure data integrity.

Many-to-many support between doctors and specializations.

One-to-one linkage between appointments and payments.

Uses AUTO_INCREMENT for primary keys and UNIQUE constraints for email and appointments.

How to run/setup the project (or import SQL)
Save your SQL script as a file, e.g., healthcare_db.sql

Open terminal or command prompt
Run:mysql -u your_username -p

Create a new database:CREATE DATABASE healthcare_db;
USE healthcare_db;

Exit MySQL prompt (exit;), then import your file:mysql -u your_username -p healthcare_db < path/to/healthcare_db.sql

link to my project ERD: https://chatgpt.com/s/m_6828a5c7e31c8191a891fda046e38de7
