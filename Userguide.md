# User Guide for Budget Tracker

## Subtitle Introduction

The Budget Tracker Program is a Python-based terminal system designed to help users manage their personal budget and track their daily expenses easily.

The system:

* Tracks different types of expenses
* Calculates the remaining budget automatically
* Prevents overspending
* Displays a summary of all expenses
* Generates a text file report of the user's transactions

## Subtitle System Requirements

Before running the system, make sure you have:

* Python 3 Installed
* A terminal or command prompt
* Type on the terminal (python --version)

## Subtitle How to run the program

Save the file - Save the code using any filename with .py at the end
1. Example: budge_tracker.py
2. Open terminal or command prompt - Navigate to the folder where the file is saved
3. Run the program

## Subtitle Starting the system

When the program starts, the system will ask for the following:

Enter name:
Enter budget:

Example; 

Enter name: Kyle Steven Cha
Enter budget: 15000
 
After entering the information, the system displays the available months.


## Subtitle Selecting a Month

The system will display the month menu:

<img width="633" height="280" alt="image" src="https://github.com/user-attachments/assets/41453274-2f39-4066-908f-6051d8332e15" />

Choose a month by typing the corresponding number.

Example; Choose month: 6 


## Subtitle Main Expense Menu

After selecting a month, the system will display the payment categories.

<img width="625" height="180" alt="image" src="https://github.com/user-attachments/assets/642f8b12-31ea-45be-bba7-024502e397b3" />



## Subtitle Selecting an Expense Category

Choose an expense category by entering its corresponding number.

Example:

Choose a number: 2

The system will then ask for the payment amount.

Example:

<img width="622" height="74" alt="image" src="https://github.com/user-attachments/assets/ce3b5bb6-5ded-4458-9399-fe3517ac53f3" />


## Subtitle Budget Validation

The system automatically checks:

If the amount entered is greater than zero
If the remaining budget is enough

Example;
If the budget is insufficient:

Insufficient balance

If the amount entered is invalid:

Not allowed, please try again.

## Subtitle Continue or Exit

After every transaction, the system asks:

Do you want to continue (y/n):

## Subtitle Expense Summary

After finishing, the program displays the complete bill summary.

The summary includes:

Expense name
Amount spent
Percentage used
Visual budget bar

Example Output:

<img width="619" height="193" alt="image" src="https://github.com/user-attachments/assets/2e74c2a2-2176-4b39-ad54-18c814b28071" />


## Subtitle Total Budget Summary

The system also displays:

Total Spent
Remaining Budget

Example:

<img width="611" height="129" alt="image" src="https://github.com/user-attachments/assets/0d8c75ba-c2c0-459e-a548-585b168a8430" />

## Subtitle Text File Generation

After the session ends, the program automatically creates a text file using the user's name.

Example:

<img width="618" height="42" alt="image" src="https://github.com/user-attachments/assets/360aa6c3-2044-4d2a-9d1d-09f9542173e1" />


The text file contains:

Expense records
Percentages
Total spent
Remaining budget

The file is saved in the same folder as the Python program.

## Subtitle Percentage Bar Visualization

The program uses a visual percentage bar to represent budget usage.

Example:

|******--------------|
Meaning:
"*" = Used budget
"-" = Remaining budget

The higher the number of *, the more budget has been used.


## Subtitle Error Handling
Error:
* Invalid choice
* Insufficient balance
* Invalid amount
* Program crash 

Cause:
* Wrong menu number entered 
* Expense exceeds remaining budget
* Negative or zero amount entered
* Non-numeric input

Solution:
* Enter valid option only

## Subtitle Features of the System
* Automated budget tracking
* Expense monitoring
* Overspending prevention
* Budget percentage computation
* Visual progress bar display
* Text file report generation
* Multiple expense category management

## Subtitle Developers
- Leopoldo Lasam
- Prince Jerickson Garcia
- John Edrian Buenavente
- Kyle Steven Cha
- John Brylle Azuela

## Subtitle Conclusion

The Budget Tracker Program helps users manage their expenses efficiently by automating budget calculations and expense tracking. It provides an easy and beginner-friendly way to monitor spending habits while practicing basic Python programming concepts.
