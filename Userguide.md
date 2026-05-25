
User Guide for Budget Tracker

**Introduction**

The Budget Tracker Program is a Python-based terminal system designed to help users manage their personal budget and track their daily expenses easily.

The system:

Tracks different types of expenses
Calculates the remaining budget automatically
Prevents overspending
Displays a summary of all expenses
Generates a text file report of the user's transactions

System Requirements

Before running the system, make sure you have:

Python 3 Installed
A terminal or command prompt
Type on the terminal (python --version)

How to run the program

Save the file - Save the code using any filename with .py at the end
Example: budge_tracker.py
2. Open terminal or command prompt - Navigate to the folder where the file is saved
3. Run the program

Starting the system

When the program starts, the system will ask for the following:

Enter name:
Enter budget:

Example; 

Enter name: Kyle Steven Cha
Enter budget: 15000
 
After entering the information, the system displays the available months.


Selecting a Month

The system will display the month menu:

[0] This month
[1] January
[2] February
[3] March
...
[12] December
Choose a month by typing the corresponding number.

Example; Choose month: 6 


Main Expense Menu

After selecting a month, the system will display the payment categories.

=====Payments=====
|1| Savings
|2| Food
|3| Electricity
|4| Water
|5| Transportation Expenses
|6| Essential Clothing
|7| Others...


Selecting an Expense Category

Choose an expense category by entering its corresponding number.

Example:

Choose a number: 2

The system will then ask for the payment amount.

Example:

-Paying Food
Please enter amount: 500

Budget Validation

The system automatically checks:

If the amount entered is greater than zero
If the remaining budget is enough

Example;
If the budget is insufficient:

Insufficient balance

If the amount entered is invalid:

Not allowed, please try again.

Continue or Exit

After every transaction, the system asks:

Do you want to continue (y/n):

Expense Summary

After finishing, the program displays the complete bill summary.

The summary includes:

Expense name
Amount spent
Percentage used
Visual budget bar

Example Output:
================================================
            TOTAL BILL
================================================

Food              : P  500.00   4.2% |*-------------------|
Electricity       : P 1000.00   8.3% |**------------------|
Transportation Expenses: P  700.00   5.8% |*-------------------|

Total Budget Summary

The system also displays:

Total Spent
Remaining Budget

Example:

================================================
Total Spent       : P 2200.00  18.3% |****----------------|
Remaining Budget  : P 9800.00  81.7% |****************----|

Text File Generation

After the session ends, the program automatically creates a text file using the user's name.

Example:

John.txt file loaded

The text file contains:

Expense records
Percentages
Total spent
Remaining budget

The file is saved in the same folder as the Python program.

Percentage Bar Visualization

The program uses a visual percentage bar to represent budget usage.

Example:

|******--------------|
Meaning:
* = Used budget
- = Remaining budget

The higher the number of *, the more budget has been used.


Error Handling
Error:
Invalid choice
Insufficient balance
Invalid amount
Program crash 

Cause:
Wrong menu number entered 
Expense exceeds remaining budget
Negative or zero amount entered
Non-numeric input

Solution:
Enter valid option only

Features of the System
Automated budget tracking
Expense monitoring
Overspending prevention
Budget percentage computation
Visual progress bar display
Text file report generation
Multiple expense category management

Technologies Used
Python
Lists and Tuples
Loops
Conditional Statements
Functions
File Handling

Conclusion

The Budget Tracker Program helps users manage their expenses efficiently by automating budget calculations and expense tracking. It provides an easy and beginner-friendly way to monitor spending habits while practicing basic Python programming concepts.

