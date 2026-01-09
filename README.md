# Personal Finance Manager – Python Project

## Introduction
Managing daily expenses is something everyone struggles with, but most beginners
never get a chance to build a real system that handles data properly.

This project is a command-line based Personal Finance Manager developed using Python.
It allows users to record expenses, store them permanently, analyze spending patterns,
and generate meaningful reports.

The main purpose of this project is not just expense tracking, but to demonstrate
how a real-world Python application is designed using Object-Oriented Programming,
file handling, validation, modular code structure, and basic data analysis.

## Why This Project Was Built
This project was built as part of a learning and evaluation task to:
- Understand how real applications store and manage data
- Practice Object-Oriented Programming in Python
- Learn how to design clean and modular code
- Handle user input safely and professionally
- Simulate real-world software development practices

Instead of writing small scripts, this project focuses on building a complete system
from scratch.

## What This Project Does
The Personal Finance Manager allows users to:
- Add daily expenses with details such as amount, category, date, and description
- View all previously recorded expenses
- Analyze spending category-wise (Food, Transport, etc.)
- Generate monthly reports to understand spending trends
- Store all data persistently using CSV files
- Create backup copies of stored data for safety
- Interact with the system using a simple, menu-driven interface

## Features in Detail

### Expense Tracking
Each expense is treated as an object with clearly defined attributes.
This makes the system structured and easy to expand in the future.

### Persistent Storage
All expenses are saved in CSV format so that:
- Data is not lost when the program stops
- Files remain human-readable
- No external database is required

### Input Validation & Error Handling
The system validates:
- Expense amount (must be a positive number)
- Date format (YYYY-MM-DD)
- Menu choices

This prevents crashes and ensures smooth user experience.

### Reporting & Analysis
The application provides:
- Category-wise spending summaries
- Monthly expense reports
- Clear formatted output for easy understanding

### Modular Code Structure
The code is divided into multiple modules, each responsible for one task.
This follows real-world software engineering practices.

---

## Technologies & Tools Used
- Python 3
- CSV module (Python standard library)
- Object-Oriented Programming
- Command-Line Interface
- VS Code for development

No external libraries were used, keeping the project lightweight and portable.

## Project Structure Explained
personal-finance-manager/
│
├── README.md # Project overview
├── requirements.txt # Dependencies
├── main.py # Application entry point
│
├── src/
│ ├── expense.py # Expense class definition
│ ├── file_manager.py # CSV read/write and backup logic
│ ├── menu.py # User menu interface
│ ├── reports.py # Expense analysis and reporting
│ ├── utils.py # Input validation utilities
│
├── data/
│ ├── expenses.csv # Stored expense data
│ └── backup_expenses.csv # Backup file
│
├── docs/
│ ├── user_guide.md
│ ├── project_explanation.md
│ └── learning_outcomes.md
│
├── tests/
│ └── README.md
│
└── screenshots/
└── sample_output.png

## How to Run the Application
1. Install Python 3 (recommended version 3.10 or above)
2. Clone the repository
3. Navigate to the project directory
4. Run the program using:
```bash
python main.py

