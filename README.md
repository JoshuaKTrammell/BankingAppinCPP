# BankingAppinCPP

Overview: 

The BankingApp is a simple console-based application written in C++ that simulates the calculation of account balances and interest earned with and without monthly deposits. The application takes user inputs such as initial investment amount, monthly deposit, annual interest rate, and the number of years, and then generates a report with detailed information for each year.

Features:
Balance Calculation Without Monthly Deposits: Displays the year-end balance and earned interest without any additional monthly deposits.

Balance Calculation With Monthly Deposits: Displays the year-end balance and earned interest with additional monthly deposits.

Detailed Yearly Report: Provides a detailed report of each year’s balance and the interest earned.

BankingApp class:

Data Members:

  * double m_initialAmount: The initial amount of money invested.
  * double m_monthlyDeposit: The amount deposited each month.
  * double m_annualInterest: The annual interest rate.
  * int m_numberOfYears: The number of years for the investment.

Member Functions: 

  * void displayDataInput() const: Displays the user's input data.
  * double calculateBalanceWithoutMonthlyDeposit(double initialInvestment, double interestRate, int numberOfYears) const: Calculates and returns the year-end balance and interest earned without additional monthly deposits.
  * double balanceWithMonthlyDeposit(double initialInvestment, double monthlyDeposit, double interestRate, int numberOfYears) const: Calculates and returns the year-end balance and interest earned with additional monthly deposits.
  * void printDetails(int yearIndex, double balance, double interestEarnedThisYear) const: Prints the details of a particular year.
  * void displayReport() const: Generates and displays the final report with all calculations.

Requirements:
  * A C++ compiler
  * A terminal or console

Instructions:
  * Open and run the files in the compiler
  * Enter the data in each line:
      * Initial Investment
      * Monthly Deposit
      * Annual Interest
      * Number of years
  * Press any key to display the results
  
  
Note: There is a flowchart that demonstrates how the program runs.

  

