# Project Analysis
# This project provides a comprehensive analysis of the stock performance for three major telecom companies: AT&T, T-Mobile, and Verizon for the year 2017. The analysis focuses on three key metrics:


# Telecom Stock Analysis - 2017

# 1. Quarterly Percentage Change in Stock Prices
# 2. Quarterly Stock Trading Volume
# 3. Quarterly Volatility (Standard Deviation of Daily Returns)

# Data Preparation
# The data was sourced from the Nasdaq Data API and includes daily stock prices and trading volumes for AT&T, T-Mobile, and Verizon.
# Date Conversion: The 'Date' column was converted to datetime format.
# Sorting: The data was sorted by 'Company' and 'Date'.
# Handling Missing Values: Forward fill and backward fill methods were applied to handle missing values.
# Save into CVS File for easier manipulation with pandas.

# Analysis and Results
# A. Quarterly Percentage Change in Stock Prices

# 1. AT&T showed a mix of positive and negative changes, with a significant decline in Q1 and a recovery in Q3.
# 2. T-Mobile displayed the highest volatility with large swings, indicating higher risk and potential for gains.
# 3. Verizon had moderate changes, showing a balance between stability and growth.

# B. Quarterly Stock Trading Volume
# Calculation: The total stock volume for each quarter was summed to understand trading activity.

# 1. AT&T consistently had the highest trading volumes, indicating high liquidity.
# 2. T-Mobile had the lowest trading volumes, suggesting lower investor interest.
# 3. Verizon showed moderate trading volumes, reflecting steady investor interest.

# C. Quarterly Volatility (Standard Deviation of Daily Returns)
# Calculation: The standard deviation of daily returns within each quarter was calculated to measure volatility.

# 1. AT&T exhibited the lowest volatility, indicating a more stable stock.
# 2. T-Mobile showed the highest volatility, indicating higher risk.
# 3. Verizon had moderate volatility, offering a balance between stability and risk.

# Conclusion
# 1. T-Mobile offers high growth potential but comes with higher risk and volatility. Suitable for investors seeking high returns and willing to accept higher risk.
# 2. AT&T provides stable performance with high liquidity, making it ideal for conservative investors looking for lower risk.
# 3. Verizon presents a balanced option with moderate growth and volatility, suitable for investors looking for a mix of stability and growth.

# Recommendations: 
# 1. T-Mobile is recommended for those seeking aggressive growth.
# 2. AT&T is recommended for those seeking stability and high liquidity.
# 3. Verizon is recommended for those looking for a balanced investment option.