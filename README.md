# Challenge assignment for Module 2

My program answers the following user story requirement: As a user, I need the ability to save the qualifying loans to a CSV file so that I can share the results as a spreadsheet.

When the following values are entered (path to a rate sheet/credit score/current amount of monthly debt/total monthly income/desired loan amount/home value), the following values are calculated given those values: monthly debt to income ratio, loan to value ratio, the number of qualifying loans. Once that is calculated, the user will be asked if they want to save the qualifying loans to a file. If the answer is 'Yes', they will be prompted to enter where they would like to store the .csv file on the local host.

## Technologies

The app.py program was written using Python version 3.11. 

## Installation Guide

The Python modules listed below were used for this program to work. 

![title](images/python_modules.png)

A qualifier folder that contains all of the functions imported into the main app, organized into two subfolders:
* filters, which includes .py files for all of your filter functions
  * contains the following files: credit_score.py, debt_to_income.py,      loan_to_value.py, max_loan_size.py
* utils, which includes your financial calculator module and your fileio module
  * contains the following files: calculators.py, fileio.py

## Usage

This screen capture shows when a path is entered and there are no issues. 

![title](images/test.png)

This screen capture shows when an invalid path is entered to save the .csv file. 

![title](images/wrong_path.png)

## Contributors

Akaron Davis

## License

The files used are not to be used by others. 
