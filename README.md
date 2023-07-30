# python-challenge

## Financial Analysis Summary

This Python script reads financial data from a CSV file named "budget_data.csv" and performs analysis on the data to provide key insights into the financial performance.

### Libraries Used:
- The code uses two libraries:
  - `pathlib` to handle file paths.
  - `csv` to read data from the CSV file.

### Input Data:
- The input data is stored in the "budget_data.csv" file, which is expected to have two columns: "Date" and "Profit/Losses."
- The data should not have any missing values or incorrect formatting for accurate results.

### Output:
- The script will generate an output text file named "MainText.txt" with the financial analysis results.

### Analysis Performed:
1. The script reads the CSV file and calculates the following financial metrics:
   - Total number of months included in the dataset.
   - Net total amount of "Profit/Losses" over the entire period.
   - Average change in "Profit/Losses" between months.
   - Greatest increase in profits (amount and corresponding date).
   - Greatest decrease in losses (amount and corresponding date).

2. It then prints the analysis results to the console:
   - Total months.
   - Total amount of profits/losses.
   - Average change in profits/losses.
   - Date and amount of the greatest increase in profits.
   - Date and amount of the greatest decrease in losses.

### How to Use:
1. Place the "budget_data.csv" file in the same directory as the script.
2. Run the script using a Python interpreter (e.g., `python script_name.py`).
3. The script will display the financial analysis on the console and create "MainText.txt" with the same information.

Please ensure that the necessary Python libraries are installed before running the script.
