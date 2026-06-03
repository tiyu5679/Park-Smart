# Park-Smart

## Overview

Park-Smart is a Python-based Parking Lot Management System designed to simulate real-world parking operations through a command-line interface. The application allows users to manage vehicle entry and exit, monitor parking space availability, view vehicle information, and calculate parking charges based on parking duration and vehicle type.

This project demonstrates the practical application of Object-Oriented Programming (OOP), data structures, file handling, and system design concepts.

## Features

* Manage vehicle entry and exit operations
* Track parking space occupancy in real time
* Store vehicle details including type and license plate number
* Calculate parking charges based on parking duration
* Support for Cars, Trucks, and Motorcycles
* View parked vehicle information
* Prevent duplicate vehicle entries
* Configurable parking lot size through configuration settings
* Command-line interface for parking management
* Demo mode for testing and simulation

## Technologies Used

* Python
* Object-Oriented Programming (OOP)
* File Handling
* Lists and Custom Data Structures
* Time and Date Management

## System Architecture

The application is built around two primary classes:

### Vehicle

The Vehicle class stores vehicle-related information, including:

* Vehicle Type
* License Plate Number
* Entry Timestamp

### Space

The Space class manages parking spaces by:

* Tracking occupancy status
* Assigning vehicles to parking spaces
* Removing vehicles upon exit
* Maintaining parking slot information

## Project Structure

```text
Park-Smart
│
├── main.py
├── config.txt
├── README.md
└── .gitignore
```

## How the System Works

1. The user selects a parking slot for a vehicle.
2. The system validates slot availability.
3. Vehicle details are stored along with the entry time.
4. Parking space occupancy is updated in real time.
5. Users can view information about parked vehicles.
6. Upon vehicle exit, the system calculates parking charges based on the parking duration and vehicle type.
7. The parking slot becomes available for future use.

## Parking Rates

| Vehicle Type | Rate Per Hour |
| ------------ | ------------- |
| Car          | Rs 30         |
| Truck        | Rs 45         |
| Motorcycle   | Rs 20         |

## Getting Started

### Prerequisites

* Python 3.x

### Clone the Repository

```bash
git clone https://github.com/patelrishi2308/Parking-Lot-Management-System.git
```

### Navigate to the Project Directory

```bash
cd Parking-Lot-Management-System
```

### Run the Application

```bash
python main.py
```

## Learning Outcomes

This project helped strengthen knowledge in:

* Object-Oriented Programming
* Class and Object Design
* Encapsulation
* Data Structures
* File Handling
* Time-Based Calculations
* Input Validation
* Command-Line Application Development
* Problem Solving and System Design

## Future Enhancements

* Graphical User Interface (GUI)
* Database Integration
* Online Parking Reservation System
* User Authentication and Authorization
* Automated Payment Processing
* Parking Analytics and Reporting Dashboard

