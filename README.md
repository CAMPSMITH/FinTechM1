# FinTechM1
Berkely FinTech Bootcamp Module 1 Challenge

## Submitted by Martin Smith
## Due date: 2022-04-03

# Running the module file
The file for this challenge is located in the **src** folder.
To run from the root of this repo
   * start the dev VM
   * run python
   * deactivate VM when done 
```
conda activate dev
python src/loan_analyzer.py
conda deactivate
``` 

# Grading Rubric
| Section    |      Element                                                 |  Pts  |  Done |
|------------|--------------------------------------------------------------|:-----:|:-----:|
| Automation | Calculate the total number of loans                          |   2   |   x   |
| Automation | Calculate the total value (sum)                              |   2   |   x   |
| Automation | calculate the average loan price                             |   2   |   x   |
| Automation | Print calculations with descriptive message                  |   2   |   x   |
| Automation | Run without error                                            |   2   |   x   |
| Analysis   | Extract future value and remaining months                    |   5   |   x   |
| Analysis   | Calculate the fair value                                     |   5   |   x   |
| Analysis   | Print the loan's fair value using condition                  |   5   |   x   |
| Analysis   | Analyze the loan value                                       |   5   |   x   |
| Financial Calculations | Create a new function to calculate present value |  10   |   x   |
| Financial Calculations | Use a function to calculate the present value    |  10   |   x   |
| Filter Lists of Loans | Create an empty list                              |  1    |   x   |
| Filter Lists of Loans | Use a for loop to select loans                    |  3    |   x   |
| Filter Lists of Loans | Append inexpensive loans to list                  |  3    |   x   |
| Filter Lists of Loans | Print the inexpensive loans list                  |  3    |   x   |
| Save Results | Use with open top open csv file                            |  2    |   x   |
| Save Results | Create csv writer                                          |  2    |   x   |
| Save Results | Use csv writer to write header                             |  2    |   x   |
| Save Results | Use for loop to iterate through inexpensive loans          |  2    |   x   |
| Save Results | Use csv writer to write loans to csv file                  |  2    |   x   |
| Coding Conventions and Formatting | Move imports to the top of the file   |  3    |   x   |
| Coding Conventions and Formatting | Name functions and variables          |  2    |   x   |
| Coding Conventions and Formatting | Follow DRY principle                  |  3    |   x   |
| Coding Conventions and Formatting | Use concise logic                     |  2    |   x   |
| Deployment and Submission | Be contained in a GitHub repository           |  5    |   x   |
| Deployment and Submission | Contain appropriate commit messages           |  5    |   x   |
| Comments | Be well commented with concise, relevant notes                 |  10   |   x   |

# Sample execution output
```
Automation
----------------------
total number of loans: 5
total value of loans: 2750
average loan price: 550.0

Analysis
----------------------
Future Value of loan: 1000
Remaining Months of loan: 9
Present Value: 861.77
loan with a present value of 861.77 is at least worth the cost of 500.00

Financial Calculations
----------------------
The present value of the new loan is: 820.08

Filter Lists of Loans
----------------------
inexpensive loans:
   0 - {'loan_price': 500, 'remaining_months': 13, 'repayment_interval': 'bullet', 'future_value': 1000}
   1 - {'loan_price': 200, 'remaining_months': 16, 'repayment_interval': 'bullet', 'future_value': 1000}

Save Results
----------------------
saved inexpensive loans to inexpensive_loans.csv

```