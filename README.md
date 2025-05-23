# 

# ✈️ Airline Ticket Reservation System 📋

Welcome to the **Airline Ticket Reservation System** project! This project is a comprehensive implementation of a flight booking system using Python with a GUI designed in **CustomTkinter**. It also incorporates CSV files for data storage, using **Pandas** for data manipulation and retrieval. This README will guide you through the setup, features, and the technical aspects of the project.

## 📑 Table of Contents

- [🎯 Project Overview](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [🛠️ Features](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [📋 Prerequisites](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [📦 Installation](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [🚀 Usage](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [📊 Analysis and Algorithms](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
    - [🔀 Dijkstra Algorithm for Flight Routes](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [📸 Screenshots](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [📜 License](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)
- [📞 Contact](https://www.notion.so/1fcb9e75448e80f2b2aec2e2d39643f7?pvs=21)

## 🎯 Project Overview

This Airline Ticket Reservation System is designed to provide an intuitive GUI-based platform for users to search and book flights. It consists of several key functionalities including user registration, flight search, booking, and payment handling. The application aims to make the flight booking process efficient and user-friendly.

The system consists of:

- **User Sign In / Registration Page**
- **Admin Login for Flight Management**
- **Flight Search & Booking**
- **Seat Selection**
- **Passenger Information Form**
- **Payment Gateway Integration**
- **Booking History View**

Data is stored in CSV files, and operations like sorting by flight price (low to high/high to low) and filtering by flight duration are handled seamlessly with **Pandas**.

## 🛠️ Features

- 🌐 **User Authentication** (Registration & Login)
- 🔍 **Flight Search** with sorting and filtering
- 🛫 **Seat Selection** Interface
- 📑 **Passenger Information** Collection
- 💳 **Payment System** (Mock implementation)
- 📚 **View Booking History**
- 🛡️ **Admin Panel** for managing flights
- 📊 **Data Analysis** using CSV

## 📋 Prerequisites

Make sure you have the following installed:

- **Python 3.7+**
- Required Python libraries:
    
    ```python
    pip install customtkinter pandas tkcalendar
    
    ```
    
- CSV files for storing flight data and user information.

## 📦 Installation

1. **Clone the Repository**:
    
    ```bash
    git clone <https://github.com/yourusername/Airline_Reservation_system.git>
    cd Airline_Reservation_system
    
    ```
    
2. **Install Dependencies**:
    
    ```bash
    pip install -r requirements.txt
    
    ```
    
3. **Run the Application**:
    
    ```bash
    python main.py
    
    ```
    

## 🚀 Usage

### 1. User Registration

Sign up for a new account or log in using existing credentials. This allows users to access flight search, booking, and other features.

### 2. Admin Log In and Flight Management

Admins can log in with special credentials to manage the flight database. Admin capabilities include:

- **Add a Flight**: Input flight details to add a new flight to the system.
- **Delete a Flight**: Remove a flight from the database if it is no longer available.
- **Modify a Flight**: Update flight details such as schedule, price, or available seats.

### 3. Flight Search

Enter departure location, destination, travel date, and other necessary details to find available flights.

### 4. Booking

Choose a preferred flight, select seats, and enter passenger information to complete the reservation.

### 5. Payment

Complete the booking by proceeding through a mock payment interface. Review the booking summary and confirm payment.

### 6. View Bookings

Access and manage your booking history at any time. This section provides a summary of all past and current reservations.

## 📊 Analysis and Algorithms

### 🔀 Dijkstra Algorithm for Flight Routes

The system incorporates the **Dijkstra Algorithm** to calculate the shortest path between two airports in terms of travel time or cost. This algorithm is essential for:

- **Optimizing flight routes** for display.
- Allowing users to see the most efficient travel options based on their search criteria.
- Handling the underlying graph structure that represents interconnected airports and available flights.

Here's a brief explanation of the algorithm:

> Dijkstra's Algorithm is used to find the shortest path from a source node to all other nodes in a graph. It works by iteratively selecting the node with the smallest known distance, updating the distances to its neighbors, and marking it as "visited."
> 

This functionality is key for providing users with accurate and optimized flight options, enhancing the overall user experience. Additionally, it helps to sort the available flights based on the **total travel time** efficiently.
