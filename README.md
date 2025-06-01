# Airline Reservation System

A simple Java-based Airline Reservation System that allows passengers to book seats on available flights. The system demonstrates basic object-oriented programming concepts including classes, objects, and relationships between them.

## Features

- Create flights with a set number of seats
- Register passengers
- Allow passengers to reserve available seats
- Prevent double-booking of seats
- View all reservations made by each passenger

## Classes Overview

- **`Passenger`**: Represents a user who can book a seat on a flight.
- **`Flight`**: Contains flight details and manages its available seats.
- **`Seat`**: Represents an individual seat with availability status.
- **`Reservation`**: Links a passenger, flight, and seat with a status.
- **`AirlineReservationSystem`**: Main class that demonstrates the system's functionality.

## How It Works

1. Flights are created with a unique flight number, destination, and number of seats.
2. Passengers are created with a unique ID, name, and email.
3. Passengers can make reservations on flights if seats are available.
4. Reservation status is stored and can be viewed per passenger.

## How to Run

1. Make sure Java is installed on your system (Java 8 or higher).
2. Save the code in a file named `AirlineReservationSystem.java`.
3. Compile the program using:

   ```bash
   javac AirlineReservationSystem.java
