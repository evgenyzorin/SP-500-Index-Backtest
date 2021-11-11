# :chart_with_upwards_trend: S&P 500 Index vs S&P 500 Sectors Portfolio
The goal of the project is to test how well a portfolio consisting of different sectors of the S&P 500 index performs relative to the benchmark S&P 500 index.

The original data was found on the official [S&P 500 Global](https://www.spglobal.com/spdji/en/index-family/equity/us-equity/sp-sectors) website and contains 11 datasets in .xls format for the last 10+ years.

The data was previously merged from two groups of datasets ([old data](https://github.com/evgenyzorin/SP-500-Index-Backtest/tree/main/old_data) from 28.02.2011 to 25.03.2021 and [new data](https://github.com/evgenyzorin/SP-500-Index-Backtest/tree/main/new_data) from 31.12.2020 to 16.09.2021) and cleaned, and is loaded into this project as one final dataset in .csv format.

### Benchmark Index:
- S&P 500

### Portfolio consists of S&P 500 Capped 35/20 Sector Indexes:
- Communication Services
- Consumer Discretionary
- Consumer Staples
- Energy
- Financials
- Health Care
- Industrials
- Information Technology
- Materials
- Utilities

### User-defined Parameters:
- Deposit = One-off amount
- Payment = Recurring Monthly Payment
- Factors = Sector Allocation (sp_500 is ALWAYS equal to 1, since it is the benchmark. The sum of the other factors forming the portfolio is also ALWAYS equal to 1)
