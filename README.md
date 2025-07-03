# Airline Ticket Reservation System

Welcome to the **Airline Ticket Reservation System** project. This project is a comprehensive implementation of a flight booking system using Python with a GUI designed in **CustomTkinter**. It also incorporates CSV files for data storage, using **Pandas** for data manipulation and retrieval. This README will guide you through the setup, features, and technical aspects of the project.

**Refer to `output.pdf` for output images.**

---


## Project Overview

This Airline Ticket Reservation System is designed to provide an intuitive GUI-based platform for users to search and book flights. It consists of several key functionalities including user registration, flight search, booking, and payment handling. The application aims to make the flight booking process efficient and user-friendly.

The system includes:

* User Sign-In / Registration Page
* Admin Login for Flight Management
* Flight Search and Booking
* Seat Selection
* Passenger Information Form
* Payment Gateway Integration
* Booking History View

Data is stored in CSV files, and operations like sorting by flight price (low to high/high to low) and filtering by flight duration are handled with **Pandas**.

---

## Features

* User Authentication (Registration and Login)
* Flight Search with sorting and filtering
* Seat Selection Interface
* Passenger Information Collection
* Payment System (Mock implementation)
* View Booking History
* Admin Panel for managing flights
* Data Analysis using CSV

---

## Prerequisites

Make sure you have the following installed:

* Python 3.7 or higher

* Required Python libraries:

  ```bash
  pip install customtkinter pandas tkcalendar
  ```

* CSV files for storing flight data and user information

---

## Installation

1. Clone the Repository:

   ```bash
   git clone https://github.com/yourusername/Airline_Reservation_system.git
   cd Airline_Reservation_system
   ```

2. Install Dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Application:

   ```bash
   python main.py
   ```

---

## Usage

### 1. User Registration

Sign up for a new account or log in using existing credentials. This allows users to access flight search, booking, and other features.

### 2. Admin Login and Flight Management

Admins can log in with special credentials to manage the flight database. Admin capabilities include:

* Add a Flight: Input flight details to add a new flight to the system
* Delete a Flight: Remove a flight from the database if it is no longer available
* Modify a Flight: Update flight details such as schedule, price, or available seats

### 3. Flight Search

Enter departure location, destination, travel date, and other necessary details to find available flights.

### 4. Booking

Choose a preferred flight, select seats, and enter passenger information to complete the reservation.

### 5. Payment

Complete the booking through a mock payment interface. Review the booking summary and confirm payment.

### 6. View Bookings

Access and manage your booking history. This section provides a summary of all past and current reservations.

---

## Analysis and Algorithms

### Dijkstra Algorithm for Flight Routes

The system incorporates the **Dijkstra Algorithm** to calculate the shortest path between two airports in terms of travel time or cost. This algorithm is used to:

* Optimize flight routes for display
* Allow users to see the most efficient travel options
* Manage the graph structure that represents airports and flight connections

Summary of the algorithm:

> Dijkstra's Algorithm is used to find the shortest path from a source node to all other nodes in a graph. It works by iteratively selecting the node with the smallest known distance, updating the distances to its neighbors, and marking it as "visited."

This functionality provides users with accurate and optimized flight options, enhancing the user experience. It also helps sort available flights based on total travel time efficiently.

## Contributors

- [@S.P.Darshan](https://github.com/sp-darshan)
