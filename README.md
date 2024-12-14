# Python-Data-Analysis

## Overview
This project consists of two Python scripting challenges: **PyBank** and **PyPoll**. Both tasks demonstrate the application of Python programming to analyze and process real-world datasets efficiently. These scripts automate data analysis tasks that would otherwise be time-consuming and error-prone using traditional spreadsheet tools like Excel.

---

### PyBank: Financial Analysis
In this challenge, a dataset containing financial records ("Date" and "Profit/Losses") is analyzed to calculate key financial metrics. 

**Key Objectives:**
- Calculate the total number of months included in the dataset.
- Compute the net total of "Profit/Losses" over the entire period.
- Determine the changes in "Profit/Losses" over the entire period and calculate the average of those changes.
- Identify the greatest increase in profits (date and amount) and greatest decrease in profits (date and amount).

**Input:**
- `budget_data.csv` (located in the `Resources` folder):
  - Columns: `Date`, `Profit/Losses`

**Output:**
- Analysis results printed to the terminal.
- Exported text file containing the analysis results (saved in the `analysis` folder).

---

### PyPoll: Election Results Analysis
This challenge involves processing a dataset containing voting data ("Voter ID", "County", "Candidate") to calculate election results.

**Key Objectives:**
- Count the total number of votes cast.
- Generate a list of candidates who received votes.
- Calculate the percentage of votes and the total number of votes for each candidate.
- Determine the winner of the election based on the popular vote.

### PyBank: Financial Analysis
```
Financial Analysis
----------------------------
Total Months: 86
Total: $22564198
Average Change: $-8311.11
Greatest Increase in Profits: Aug-16 ($1862002)
Greatest Decrease in Profits: Feb-14 ($-1825558)
```

### PyPoll: Election Results
```
Election Results
-------------------------
Total Votes: 369711
-------------------------
Charles Casper Stockham: 23.049% (85213)
Diana DeGette: 73.812% (272892)
Raymon Anthony Doane: 3.139% (11606)
-------------------------
Winner: Diana DeGette
-------------------------
```

## Skills Demonstrated
- Python programming
- Data manipulation with CSV files
- Iterative problem-solving
- File input/output handling
- Debugging and error-free scripting
- Automation of data analysis tasks
