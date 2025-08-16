# 💰 Personal Finance Tracker

### 📌 Overview

A **command-line personal finance tracker** that helps you monitor income, expenses, and financial goals. Built with a focus on clean data management, it uses a list of dictionaries to store transaction records and provides features for searching, sorting, and summarizing your financial activity. It's a practical tool for anyone looking to get a better handle on their budget.

### 🛠 Features

  * **Transaction Logging:** Add income and expense records with date, category, description, and amount.
  * **Data Persistence:** Automatically saves your data to a `my_finances.json` file and loads it every time you start the app.
  * **Dynamic Reporting:** View all transactions in a clean, tabulated format.
  * **Advanced Search:** Search your records by category, description, date, or amount.
  * **Data Summarization:** Get a quick financial summary, including total income, expenses, and your net balance.
  * **Data Visualization:** Generate an ASCII bar chart to visualize your spending habits month by month.
  * **Secure Access:** Includes a simple, hardcoded login system to protect your financial data.
  * **Full CRUD:** Create, Read, Update (by deleting and re-adding), and **Delete** transactions.

### 📂 Data Structures & Concepts Used

  * **List of Dictionaries** → The core data structure, used to store an array of transaction records (`[{...}, {...}]`).
  * **JSON** → Used for serializing the Python list into a human-readable text file for persistent storage.
  * **File I/O** → Manages reading from and writing to the data file.
  * **Procedural Programming** → The application is organized into a set of clear, single-purpose functions.

### 🚀 How to Run

1.  **Prerequisites**
    You need to have the `tabulate` library installed. If you don't have it, run this command:

    ```bash
    pip install tabulate
    ```

2.  **Save the Code**
    Save the Python code into a file named `finance_tracker.py`.

3.  **Run from Terminal**
    Open your terminal or command prompt, navigate to the directory where you saved the file, and run the program:

    ```bash
    python finance_tracker.py
    ```

4.  **Login**
    Use the predefined credentials to log in:

      * **Username:** `Samarjit`
      * **Password:** `roy`

5.  **Use the Tracker**
    Follow the on-screen menu to manage your finances\!
