# EDX-Console-Finances

## Task
Tasked with creating code that analyses the financial records of a company. Provided with a financial dataset in `starter/index.js` file.

## Instructions
You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

Your task is to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in Profit/Losses are from month to month and then find the average.
  * (`Total/(Number of months - 1)`)

* The greatest increase in Profit/Losses (date and amount) over the entire period.

* The greatest decrease in Profit/Losses (date and amount) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis 
  ----------------
  Total Months: 86
  Total: $38382578
  Average Change: -2315.12
  Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
  Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
  ```

Your final code should print the analysis to the console.

## Workflow
I committed straight to main with very clear commit messages and history
I used ES6 JavaScript hence the change from var to let
I used temporal literals as an alternative to concatination for greater readability and to format the final result using multi-line strings & expressions

code source can be found in assets/index.js

## Installation

The challenge is deployed using Github Pages. The end result can be found here: https://reginaabena19.github.io/Console-Finances/ When viewing through the editor ensure live server is installed in order to run the index.html file in the browswer.

