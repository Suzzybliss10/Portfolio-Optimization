This is a personal assignment on the optimizzation of portfolio, with 10 selected stocks

Portfolio Optimization README
Introduction
This README provides an overview of the R code for portfolio optimization using genetic algorithms (GA). The code is divided into two parts:

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

Steps
Fetching Data and Asset Selection: Stock data for a wide range of assets is fetched, and a GA is employed to select assets based on historical performance and sector diversity.
Portfolio Optimization with Selected Assets: We use the selected assets to optimize portfolio weights using a GA, similar to Part 1.
Evaluation: We evaluate the performance of the optimized portfolio on both train and test sets.
Conclusion
Both parts demonstrate the effectiveness of GA in constructing optimized portfolios. Part 1 focuses on optimizing weights with manually selected assets, while Part 2 integrates GA-based asset selection with portfolio optimization. The code provides insights into constructing well-diversified portfolios with desirable risk-return profiles.
