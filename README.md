# loan_analyzer
A simple utility that analyzes a list of loans and fins inexpensive loans to purchase.

# Running the module file
To run from the root of this repo
   * start a VM (recommended)
   * run python
   * deactivate VM when done 
```
conda activate dev
python src/loan_analyzer.py
conda deactivate
``` 

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
        {'loan_price': 500, 'remaining_months': 13, 'repayment_interval': 'bullet', 'future_value': 1000}
        {'loan_price': 200, 'remaining_months': 16, 'repayment_interval': 'bullet', 'future_value': 1000}

Save Results
----------------------
saved inexpensive loans to inexpensive_loans.csv

```

