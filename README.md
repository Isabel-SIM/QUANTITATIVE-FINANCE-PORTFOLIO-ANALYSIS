# A Whale off the Port(folio)
Introduction
In this project, we analyse and evaluate the performance of various investment portfolios, including those managed by prominent hedge fund managers ("whales") and in-house trading algorithms. The goal is to assess how these portfolios compare to the broader stock market, represented by the S&P TSX 60 Index. We conduct quantitative analysis to measure portfolio performance, risk, and other relevant metrics.
# Getting Started
### Prerequisites
To run the analysis and code provided in this project, you need to have the following prerequisites installed.
Python (3.7 or higher)
Jupyter Notebook (for running the provided code interactively)
### Installation
Clone this repository to your local machine: 	
- git clone [https://github.com/Isabel-SIM/WEEK-FOUR-HOMEWORK/whale-portfolio-analysis.git](https://github.com/Isabel-SIM/WEEK-FOUR-HOMEWORK/blob/main/STARTER_CODE/whale_analysis.ipynb)   
- Navigate to the project directory: 	
- cd whale-portfolio-analysis 

Install the required Python packages: 
- pip install  
- Open the Jupyter Notebook file portfolio_analysis.ipynb to start exploring the analysis.
# Data Sources
The analysis relies on the following data sources:
- whale_returns.csv: Contains historical returns of well-known hedge fund portfolios.
- algo_returns.csv: Contains returns from in-house trading algorithms.
- sp_tsx_history.csv: Provides historical closing prices of the S&P TSX 60 Index.
# Data Cleaning
Before performing any analysis, the data is cleaned and prepared. This includes handling missing values, combining datasets, and ensuring consistency. Detailed data cleaning steps are provided in the project code.
# Quantitative Analysis
The quantitative analysis is divided into several sections, each focusing on different aspects of portfolio evaluation.
# Performance Analysis
### Calculate and Plot Daily Returns
- We calculate and visualise the daily returns of all portfolios to understand their performance over time.
### Calculate and Plot Cumulative Returns
- We compute and plot the cumulative returns of the portfolios to assess long-term performance.
### Risk Analysis
- We analyse the risk associated with each portfolio compared to the S&P TSX 60 Index.
### Create a Box Plot for Each Portfolio
- Box plots are used to visually represent the distribution of daily returns for each portfolio.
### Calculate Standard Deviations
- We calculate the daily standard deviations of portfolio returns as a measure of risk.
### Determine Which Portfolios Are Riskier Than the S&P TSX 60
- We identify portfolios that exhibit higher risk levels than the S&P TSX 60 Index.
### Calculate the Annualised Standard Deviation
- The annualised standard deviation is computed to assess risk on an annual basis.
### Rolling Statistics
- Risk and other metrics change over time. We analyse rolling statistics to capture these changes.
### Calculate and Plot the Rolling Standard Deviation 
- We calculate rolling standard deviations to visualise how portfolio risk evolves over time.
### Calculate and Plot the Correlation
- Correlations between portfolio returns and the S&P TSX 60 Index are computed and visualised.
###  Calculate and Plot Beta for a Portfolio Compared to the S&P TSX 60
- Beta values, which measure a portfolio's sensitivity to market movements, are calculated and visualised.
### Rolling Statistics: Exponentially Weighted Average
- We calculate and plot the exponentially weighted moving average (EWMA) for a portfolio to analyse trends.
###  Sharpe Ratios
- Sharpe ratios are used to assess risk-adjusted returns.
###  Calculate the Annualised Average Return and Sharpe Ratios
- We calculate the annualised average return and Sharpe ratios for each portfolio.
###  Visualise the Sharpe Ratios as a Bar Plot
- Sharpe ratios are visualised to compare the risk-adjusted performance of different portfolios.
###  Determine Whether the Algorithmic Strategies Outperform the Market
- We assess whether the algorithmic trading strategies outperform the S&P TSX 60 Index in terms of risk-adjusted returns.

<br>

This project provides valuable insights into portfolio performance and risk, helping investors make informed decisions.
