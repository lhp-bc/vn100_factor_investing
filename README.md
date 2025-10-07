# vn100_factor_investing
Backtest a simple factor investing strategy on VN100 (2020–2025)
# Factor Investing Strategy on VN100 (2020–2025)

This project was done as part of the Miquant Quant Intern assignment.  
It backtests a simple multi-factor strategy using **VN100** stocks from **January 2020 to October 2025**.

🔹 Objective
To design and test a basic **factor investing** strategy using price and financial data from the Vietnam stock market.

🔹 Methodology
- **Universe:** VN100 constituents  
- **Data:** Daily price and volume from `vnstock` library  
- **Factors:**
  - Momentum (12–1 month)
  - Value (Book-to-Market ratio)
  - Quality (ROE TTM)
- **Portfolio construction:**
  - Top 20 stocks with highest combined score
  - Equal weight, rebalanced monthly
  - Transaction cost: 0.3% per side, 0.1% sell tax
- **Benchmark:** VNINDEX

🔹 Results
| Metric | Value |
|---------|-------|
| CAGR | XX% |
| Volatility | XX% |
| Sharpe Ratio | XX |
| Max Drawdown | XX% |

🔹 Folder Structure
