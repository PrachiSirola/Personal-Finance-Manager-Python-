# docs/user_guide.md

```md
# User Guide – Personal Finance Manager

## Introduction
This guide explains how to use the Personal Finance Manager application step by step.
No prior technical knowledge is required.

## Starting the Application
1. Open terminal or command prompt
2. Navigate to the project folder
3. Run:
   python main.py

You will see the main menu.

## Understanding the Menu

### 1. Add New Expense
Use this option to record a new expense.
You will be asked to enter:
- Amount (example: 1500)
- Category (Food, Transport, Shopping, etc.)
- Date (format: YYYY-MM-DD)
- Description (short note)

The expense is saved automatically.

### 2. View All Expenses
Displays all previously saved expenses in a clean format.

Example:
2024-01-15 | Food | ₹1500 | Grocery Shopping

### 3. View Category-wise Summary
Shows total spending grouped by category.
This helps identify where most money is being spent.

### 4. Generate Monthly Report
Enter a month (YYYY-MM) to see only expenses from that month.

Example:
2024-01

### 5. Backup Data
Creates a backup copy of all expense data.
This ensures data safety.

### 6. Exit
Safely exits the application.

## Error Messages
If incorrect input is entered:
- The program will display an error message
- You will be asked to enter the value again
- The application will not crash

## Data Storage
All data is stored locally in CSV format inside the `data` folder.
