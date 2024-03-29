## Portfolio Optimization

This is a personal assignment on the optimizzation of portfolio, with 10 selected stocks

Portfolio Optimization README
Introduction
This README provides an overview of the R code for portfolio optimization using genetic algorithms (GA). The code is divided into two parts:

Libraries Used
The following R libraries are used in this project:

GA: for implementing genetic algorithms
quantmod: for fetching historical stock data from Yahoo Finance

Part 1: Construction of a portfolio with manually selected assets and GA-generated weights.
Part 2: Integration of asset selection using GA with portfolio optimization.
Part 1: Construction of a Portfolio
Overview
In this part, we construct a portfolio using manually selected assets and then optimize its weights using a GA.

Steps
Fetching Data: Stock data for selected assets is fetched from Yahoo Finance using the quantmod package.
Data Preparation: Monthly returns are calculated from the fetched data and split into train and test sets.
Fitness Function Definition: A fitness function is defined to maximize the Sharpe ratio, considering portfolio return and risk.
Portfolio Optimization using GA: We optimize the portfolio weights using a GA with specified parameters.
Evaluation: We evaluate the optimized portfolio on both train and test sets.
Part 2: Integration of Asset Selection with Portfolio Optimization
Overview
This part integrates asset selection using GA with portfolio optimization to enhance portfolio performance.


Contributing
Contributions to this project are welcome. You can contribute by improving existing code, adding new features, or fixing bugs. Please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License. You are free to modify and distribute the code for both commercial and non-commercial purposes.

Feel free to customize this README according to your specific project details and preferences. If you have any further questions or need assistance, please let me know!
