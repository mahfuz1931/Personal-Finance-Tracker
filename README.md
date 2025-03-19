# Personal Finance Tracker

## Overview
Personal Finance Tracker is a Python-based CLI application that helps users manage their income and expenses efficiently. Users can add transactions, view financial summaries within a specific date range, and visualize income vs. expenses using graphs.

## Features
- Add new transactions (income or expenses)
- View transaction history within a specified date range
- Generate a financial summary (Total Income, Total Expense, Net Savings)
- Visualize income and expense trends with matplotlib
- Persistent storage using CSV

## Technologies Used
- Python
- Pandas
- Matplotlib
- CSV for data storage

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/personal-finance-tracker.git
   cd personal-finance-tracker
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib
   ```

## Usage
1. Run the application:
   ```bash
   python main.py
   ```
2. Follow the prompts to:
   - Add a transaction
   - View transactions and summary
   - Exit the application

## File Structure
```
personal-finance-tracker/
│── data_entry.py    # Handles user input and validation
│── main.py          # Main program logic and user interaction
│── finance_data.csv # Stores financial records
│── README.md        # Project documentation
```

## Future Enhancements
- Add category-based filtering for transactions
- Implement a GUI version using Tkinter or PyQt
- Support for multiple users with authentication


