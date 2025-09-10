🏖️ Resort Booking System

A C++ Object-Oriented Programming (OOP) based project that simulates a resort booking system with features like user registration, room booking, activity planning, meal customization, and feedback collection.

This project showcases the use of OOP concepts, STL (Standard Template Library), and graph algorithms (Dijkstra’s algorithm) for building a real-world application.

✨ Features

User Registration

Collects details such as name, age, gender, email, and phone number.

Records group information (number of people, names, ages, and genders).

Stores details using classes and maps for efficient retrieval.

Room Booking

Multiple room options available:

Single-bed Non-AC

Single-bed AC

Double-bed Non-AC

Double-bed AC

Automatically calculates total cost based on selections.

Activity Planning

Displays a list of available activities with costs.

Calculates total cost of selected activities.

Suggests the optimal route between activity spots using Dijkstra’s Algorithm.

Meal Customization

Breakfast menu with prices.

Allows multiple selections and updates the total cost.

Feedback Collection

Users can submit reviews and feedback about their experience.

🛠️ Tech Stack & Concepts

Programming Language: C++

Paradigm: Object-Oriented Programming (OOP)

Core Concepts Used:

Classes & Objects

Arrays & Strings

Loops & Conditional Statements

Recursion

Searching & Sorting (STL)

Graphs (Dijkstra’s Algorithm)

Maps for storing data

📂 Project Workflow

User Registration → Enter user and group details.

Room Booking → Choose room types and calculate cost.

Activity Planning → Select activities and get optimal travel routes.

Meal Selection → Pick breakfast items and calculate total bill.

Feedback → Submit reviews and suggestions.

Summary → System prints all details and final bill.

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/resort-booking-system.git
cd resort-booking-system


Compile the code (using g++ for example):

g++ main.cpp -o resort


Run the program:

./resort

📸 Sample Outputs

✔️ Registration details summary
✔️ Room selection and total cost
✔️ Optimal activity route (Dijkstra’s algorithm)
✔️ Final bill with all costs

📝 Future Enhancements

Add payment gateway simulation.

Include graphical UI instead of console output.

Store user data in a database (MySQL/SQLite).

Extend meal menu beyond breakfast.

Add more optimization algorithms for planning activities.
