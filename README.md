# Data Science Assignment – Trader Behavior vs Market Sentiment

## Project Overview

This project analyzes the relationship between **trader behavior** and **market sentiment**
using two datasets:

1. **Bitcoin Fear & Greed Index** – representing historical market sentiment regimes  
2. **Hyperliquid Historical Trader Data** – representing real trade executions

The goal is to understand how profitability, trade size, risk, and trading activity
align with or diverge from market sentiment conditions such as **Fear** and **Greed**.

Note- Hyperliquid Historical Trader Data file is larger than 25MB so that we cant upload it in repo.
download it from here - https://www.kaggle.com/datasets/pradeepjswl/historical-trade-data



## Data Handling Approach

The sentiment dataset and trading dataset do not overlap temporally
(sentiment data from earlier years vs trade execution data from 2024).

To preserve data integrity:
- A direct date-level merge was **not forced**
- A **regime-based analysis approach** was adopted
- Historical sentiment patterns were analyzed independently
- Trader behavior was evaluated and compared conceptually

This approach reflects real-world data science best practices.


## Key Insights Summary

- Trader behavior shows characteristics consistent with **Greed-dominated market regimes**
- Trade size and PnL distributions are highly skewed with significant tail risk
- A small number of large trades contribute disproportionately to overall risk
- Over-trading behavior is observed among a subset of accounts
- Risk-adjusted evaluation is more informative than average PnL alone


## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab


All analysis was performed in **Google Colab**.  


- All visual outputs are saved in the `outputs/` directory
- All processed datasets used for analysis are saved in the `csv_files/` directory
- The project follows the standardized submission format provided in the assignment instructions

