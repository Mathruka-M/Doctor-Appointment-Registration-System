# Doctor Appointment Registration System

## Project Overview
This is a basic **Java Swing** desktop application connected to an **Oracle Database** using JDBC. It allows users to register, log in, reset passwords, and manage doctor appointments with a simple and interactive interface.

## Features
- **Login Page**: Enter username and password; options to register or reset password.
- **Registration Page**: Create a new user account with username and password.
- **Appointment Booking**: Select date, time, doctor, and age, then book an appointment.
- **View Appointments**: See all booked appointments for the logged-in user.
- **Cancel Appointment**: Delete a selected appointment.
- **Navigation**: Back buttons allow returning to previous pages.

## Tech Stack
- **Language:** Java (Swing for GUI)
- **Database:** Oracle SQL
- **Connectivity:** JDBC (ojdbc11.jar)

## Database Tables
- **users**: Stores username, password, and name.
- **appointments**: Stores appointment details (date, time, doctor, age, username).

## How to Run
1. Install Java (JDK 8 or above) and Oracle Database.
2. Add **ojdbc11.jar** to your project classpath.
3. Import the `users` and `appointments` tables into Oracle.
4. Compile and run the application from your IDE or terminal:
   ```bash
   javac *.java
   java LoginPage
