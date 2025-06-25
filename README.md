# Quantitative-Analysis-of-Risk-and-Return-for-a-Multi-Asset-Financial-Portfolio-Using-Python


📊 Portfolio Risk and Return Analysis (Python)
This project evaluates the risk and return characteristics of a financial portfolio composed of JPMorgan Chase (JPM), Morgan Stanley (MS), and Bank of America (BAC), benchmarked against the S&P 500 Index.

It implements a full return and risk analysis pipeline using Python, applying concepts from modern portfolio theory, the Capital Asset Pricing Model (CAPM), and Value at Risk (VaR) frameworks.


🎯 Objective
To perform a comprehensive quantitative assessment of portfolio performance by:

Calculating daily and annualized returns

Measuring volatility and downside risk

Computing risk-adjusted performance ratios

Estimating Value at Risk (VaR) and Conditional VaR

Comparing the portfolio’s performance to the market benchmark (S&P 500)



🧰 Tools & Libraries
Python

yfinance – for data collection

pandas, numpy – for data manipulation and calculations

matplotlib, plotly – for visualization



🔍 Methodology Overview
1. Data Collection
Historical daily closing prices for JPM, MS, BAC

Benchmark: S&P 500 (^GSPC)

2. Return Calculations
Daily simple returns and log returns for each stock

Portfolio returns using equal weighting (⅓ each)

3. Annualization
Annual return using compounding for simple returns

Annual volatility using scaled standard deviation

4. CAPM Metrics
Beta: Measures portfolio sensitivity to market

Alpha: Measures excess return beyond market expectations

5. Performance Ratios
Sharpe Ratio: Return per unit of total risk

Sortino Ratio: Return per unit of downside risk

Calmar Ratio: Return over maximum drawdown

Treynor Ratio: Return per unit of systematic risk (Beta)

6. Risk Measures
Historical Value at Risk (VaR) – 90% confidence level

Conditional VaR (Expected Shortfall) – Average of worst 5% returns



📊 Key Results
Metric	Value
Annualized Return	44.96%
Annual Volatility	21.31%
Alpha (vs benchmark)	17.97%
Beta	0.896
Sharpe Ratio	1.78
Sortino Ratio	2.76
Calmar Ratio	3.37
Treynor Ratio	0.42
VaR (90%)	–$12,316
Conditional VaR (5%)	–$27,814

Assumes an initial portfolio value of $1,000,000 and 252 trading days/year.





📌 Additional Notes
The portfolio is equally weighted; you can modify weights for custom strategies.

Analysis is based on historical data only — no forecasting or ML models are used.

Code is cleanly structured for extension into multi-asset or sectoral portfolios.



👤 Author
Amit Sharma
M.Sc. Mathematics | Delhi Technological University (DTU)
 Placement Coordinator

📧 Feel free to reach out for research roles, internships, or quantitative finance opportunities.
🔗 Connect with me on LinkedIn 
