# Mortgage Calculator README

This Python program is designed to calculate mortgage details and output the results in an Excel file with comprehensive formatting options. It allows users to input various parameters such as loan amount, loan lengths, interest rates, down payment percentages, and check-in points to evaluate mortgage details over time.

## Program Components

The program consists of the following components:

1. **Mortgage Calculation Function**: 
   - Calculates mortgage details including principal paid, interest paid, total payment, and principal remaining for each specified check-in year.
   - Utilizes numpy_financial library for financial calculations.

2. **Display Results Function**:
   - Displays the mortgage calculation results in a tabular format on the console.

3. **Save Results to Excel Function**:
   - Writes the mortgage calculation results to an Excel file. The file is named with an incrementing number if a file with the same name already exists, preventing overwriting of previous results.

4. **Main Function**:
   - Accepts user inputs for loan amount, loan lengths, interest rates, down payment percentages, and check-in points.
   - Calls the necessary functions to process inputs, calculate mortgage details, display results, and save results to Excel.

## Usage

To use this program:

1. Run the program.
2. Input the required parameters:
   - Loan amount
   - Number of loan lengths to compare
   - For each loan length:
     - Number of years
     - Interest rate
   - Number of down payment options
   - For each down payment option:
     - Down payment percentage
   - Number of check-in points to evaluate
   - For each check-in point:
     - Check-in year
3. View the results displayed on the console.
4. Find the Excel file containing the results in the same directory as the program. The file will be named 'Mortgage_results_1.xlsx', 'Mortgage_results_2.xlsx', etc., to avoid overwriting previous results.

## Dependencies

This program requires the following dependencies:

- `numpy_financial`: Used for financial calculations such as present value, future value, and payment calculations.
- `xlsxwriter`: Used for creating and formatting the Excel file output.

## Note

- Ensure that all input values are entered accurately to obtain correct results.
- Review the Excel file to analyze mortgage details further or for additional processing.

