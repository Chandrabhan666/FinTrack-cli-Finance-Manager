FinTrack CLI Finance Manager :-

FinTrack CLI Finance Manager is a command-line based personal finance management application developed using Python, SQLAlchemy, and SQLite. This project allows users to efficiently track their daily expenses, manage categories, set monthly budgets, handle subscriptions, and generate category-wise expense reports. It uses SQLAlchemy ORM for database management and provides a simple interactive CLI menu for performing all operations.

Features

Add new expense categories

Add expenses with title, amount, date, and category

Update existing expense details

Delete expenses from the database

Search expenses by specific date

Set monthly budget limits

Add and track subscription payments

View all active subscriptions

Generate category-wise expense report using SQL queries

Automatic database creation using SQLAlchemy

Technologies Used

Python 3

SQLAlchemy ORM

SQLite Database

Command Line Interface (CLI)

How It Works

The application creates a local SQLite database named fintrack.db and stores data in four tables:

Categories – stores expense categories

Expenses – stores expense records linked with categories

Budgets – stores monthly budget limits

Subscriptions – stores subscription payment details

Users interact with the system through a CLI menu to perform various financial management operations.

How to Run

Install SQLAlchemy:

pip install sqlalchemy


Run the program:

python main.py


Select options from the menu to manage your finances.

Example Menu Options
1. Add Category
2. Add Expense
3. Update Expense
4. Delete Expense
5. Search by Date
6. Set Budget
7. Add Subscription
8. View Subscriptions
9. Category Report
10. Exit

Purpose of Project

This project was developed to practice Python programming, SQLAlchemy ORM, database design, and CLI application development. It demonstrates how to build a complete database-driven finance management system using Python.

Author

Chandrabhan Patel
B.Tech Computer Science Student
Lovely Professional University
