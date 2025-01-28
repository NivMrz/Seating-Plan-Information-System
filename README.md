# Automated Event Seating System

## Overview

This project focuses on developing an automated information system for generating seating plans at events like weddings, using a linear programming algorithm. The system replaces the traditional manual seating arrangement process, reducing time and effort while optimizing guest placement based on predefined constraints such as table capacity and guest preferences.

## Key Features

- **Automated Guest Seating**: Uses a linear programming algorithm to assign guests to tables efficiently.
- **Data Input and Categorization**: Users can input guest lists, categorize guests, and define constraints.
- **Optimization Algorithm**: Minimizes the number of tables used while maintaining guest preferences.
- **Real-Time Adjustments**: Allows users to modify guest lists and rerun the seating arrangement.
- **Data Export**: Enables downloading the seating plan as an Excel file.
- **User-Friendly Interface**: Designed with HTML, CSS, and JavaScript for a seamless experience.

## Technical Highlights

- **Backend**: Implemented in Python using the PuLP library for linear programming.
- **Frontend**: Web-based interface built with HTML, CSS, and JavaScript.
- **Database**: Uses SQL Server for storing guest information and seating arrangements.
- **Automation**: Algorithm optimizes seating and generates an interactive seating plan.
- **Performance Optimization**: Seating plan generated in under 2 minutes for large-scale events.

## How to Use

1. **Download** ZIP file containing all needed files for running the system.
2. **Extract** files to a folder.
3. **Open SQL Server Management Studio** ([Download Link](https://aka.ms/ssmsfullsetup)).
4. **Create a new database** named `CANN`.
5. **Execute SQL Query**: Paste the text from the 'query' file into a new query to create the necessary tables.
6. **Save** the database.
7. **Open `app.py`** with a development environment software (PyCharm recommended).
8. **Ensure dependencies**: Make sure all necessary libraries are installed.
9. **Configure Server**: Change `SERVER=XXX` to your PC name under 'Your server instance' (line 29).
10. **Run the Code**.
11. **Access the System**: Open `main.html` and use the system as needed.

## Requirements

- Web browser (Google Chrome, Firefox, Edge recommended)
- Internet connection
- SQL Server for database management
- Python with the following libraries:
  - flask
  - pyodbc
  - bcrypt
  - pulp
  - threading
  - io
  - os
  - openpyxl
  - pandas

## Authors

- **Chen Biazi**
- **Noa Ezri**
- **Niv Meirovitz**
- **Alon Achituv**

## Acknowledgments

- Supervised by Dr. Gabi Pinto
- Developed as part of the *Analysis and Planning of Information Systems A* course

## Future Enhancements

- **Mobile App Integration**: Expanding functionality for mobile users.
- **Multiple Event Management**: Allowing users to manage multiple seating plans.
- **Guest Confirmation System**: Integrating RSVP tracking to adjust seating dynamically.
- **AI-based Guest Arrangement**: Enhancing the algorithm to factor in social relationships for optimal guest experience.

This system significantly reduces the complexity of event planning by automating the seating arrangement process, improving efficiency, and ensuring guest satisfaction.

