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

**Input:**
- `election_data.csv` (located in the `Resources` folder):
  - Columns: `Voter ID`, `County`, `Candidate`

**Output:**
- Election results printed to the terminal.
- Exported text file containing the election results (saved in the `analysis` folder).

---

## Project Structure
```
python-challenge/
│
├── PyBank/
│   ├── Resources/
│   │   └── budget_data.csv
│   ├── analysis/
│   │   └── financial_analysis.txt
│   └── main.py
│
├── PyPoll/
│   ├── Resources/
│   │   └── election_data.csv
│   ├── analysis/
│   │   └── election_results.txt
│   └── main.py
│
└── README.md
```

---

## Installation and Usage

### Prerequisites
- Python 3.x installed on your computer.

### Steps to Run the Scripts
1. Clone this repository to your local machine.
2. Navigate to the folder for the desired challenge (`PyBank` or `PyPoll`).
3. Ensure the necessary input CSV file is located in the `Resources` folder.
4. Run the `main.py` script using Python:
   ```bash
   python main.py
   ```
5. View the analysis results in the terminal and find the exported text file in the `analysis` folder.

---

## Example Outputs

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

---

## Skills Demonstrated
- Python programming
- Data manipulation with CSV files
- Iterative problem-solving
- File input/output handling
- Debugging and error-free scripting
- Automation of data analysis tasks
