# Expense Tracker

A simple command-line interface (CLI) Python application to track your daily expenses, log them into a local CSV file, and analyze your spending against a monthly budget.

## Features

* **Log Expenses:** Input expense details such as name, amount, and custom category.


* **Predefined Categories:** Categorize spending into 🍔 Food, 🏠 Home, 💼 Work, 🎉 Fun, or ✨ Misc.


* **Persistent Storage:** Appends all entries directly into a local `expenses.csv` file.


* **Expense Breakdown:** Summarizes total spending grouped by category.


* **Smart Budget Insights:**
* Displays total amount spent and remaining budget against a fixed $2,000 threshold.


* Calculates remaining days in the current month.


* Calculates daily recommended spending limit to stay within budget.





## Requirements

* Python 3.x

## Project Structure

```text
.
├── expense.py         # Defines the Expense data class
├── expense_tracker.py # Main logic for user input, file storage, and reporting
└── expenses.csv       # Generated file storing expense records (created automatically on run)

```

## How to Run

1. Clone the repository or download the source files.
2. Open your terminal in the project directory.
3. Execute the script:

```bash
python expense_tracker.py

```

## How It Works

1. **Input Details:** Enter the item name and amount spent.


2. **Select Category:** Pick a category from the numbered interactive menu.


3. **Save:** The program appends `name,amount,category` to `expenses.csv`.


4. **Summary Report:** View your category breakdown, remaining monthly budget, and calculated daily budget for the rest of the month.



Linkedin URL:https://lnkd.in/p/gxGrnwFt
