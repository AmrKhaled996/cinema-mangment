# Cinema Management System (CLI-Based)

## Overview
The **Cinema Management System** is a command-line application built using **Java** that allows users to manage a cinema efficiently. The system handles movies, screen times, seating arrangements, and halls where movies are displayed. It also includes a customer module for booking seats and generating receipts. Additionally, the system provides reports such as the number of seats booked per movie and the most crowded screening times.

## Features
- **Movie Management**: Add, update, and list movies categorized by genre (Action, Romantic, Horror, Comedy).
- **Screen Time Management**: Manage movie schedules, including start and end times.
- **Hall Management**: Assign movies to specific halls with defined seating arrangements.
- **Seat Classification**: Seats are divided into three classes:
  - First Class
  - Second Class
  - Third Class
- **Customer Module**:
  - Customers can order movie tickets.
  - Generate receipts for booked seats.
- **Reports & Statistics**:
  - Number of seats booked for each movie.
  - Most crowded screening time.
  - Other relevant cinema statistics.

## Technologies Used
- **Java** (Core Programming Language)
- **MySQL** (Database for storing cinema-related data)
- **JDBC** (For database connectivity)
- **Object-Oriented Programming (OOP) Principles**

## How to Run the Project
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/AmrKhaled996/cinema-mangment-system
   cd cinema-mangment-system
   ```
2. **Set Up the Database:**
   - Import the provided SQL schema into MySQL.
   - Update database credentials in the project’s configuration file.
3. **Compile & Run:**
   ```sh
   javac Main.java
   java Main
   ```
4. **Follow On-Screen Instructions** to interact with the system.

## Future Enhancements
- Add a graphical user interface (GUI) for better user experience.
- Implement online booking functionality.
- Integrate payment processing for ticket purchases.

## Contributors
- **Amr Khaled Ismail Mahanna** *(Lead Developer)*

## License
This project is open-source and available for modification and use under the MIT License.

## Project Repository
[GitHub Repository](https://github.com/AmrKhaled996/cinema-mangment-system)

