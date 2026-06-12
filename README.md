# Client Statistics Analysis

This project contains a basic statistical analysis of client data using Python, pandas and matplotlib.

## Project goal

The goal of this project is to analyze client purchase behavior, segment clients by total amount, check correlations, detect outliers and compare towns by client value.

## Dataset

The dataset contains client-level information:

- client_id — client identifier
- client_name — client name
- town — client town
- orders_count — number of orders
- total_amount — total purchase amount
- avg_order_amount — average order amount

## Tools

- Python
- pandas
- matplotlib
- Jupyter Notebook

## Analysis steps

1. Basic descriptive statistics
2. Quantiles and client segmentation
3. Manual covariance and correlation calculation
4. Correlation check with pandas
5. Outlier detection using IQR
6. Boxplot and histogram
7. Town comparison
8. Client and revenue share by town
9. Hypothesis check

## Key insights

- The most valuable clients are Sergey and Maria.
- The strongest correlation is between orders_count and total_amount.
- No statistical outliers were found using the IQR method.
- Moscow has the largest number of clients.
- Kazan contributes the largest share of total purchase amount.
- The hypothesis that clients from Kazan spend more than clients from Moscow looks supported in this small sample, but more data is needed for a strong conclusion.

## File

- `client_statistics_analysis.ipynb`
