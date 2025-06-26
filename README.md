# Computational Finance

A collection of **numerical methods** and **computational techniques** applied to **financial data analysis** and **modeling**. This repository demonstrates various approaches to solving financial problems, such as forecasting, interpolation, and more.

## 🧑‍💻 Projects in This Repo:

#### 1. 📈 Momentum-Based Stock Strategy

This project implements a **momentum investing strategy** using historical stock data from the S&P 500. It ranks stocks based on their past 6-month performance (excluding the most recent month), selects the top 20 each month, and simulates a portfolio that rebalances monthly.

#### Repository:
Check this project out on [This Repo](https://github.com/KlarenceKPIs/momentum-strategy).
---

## 🔧 Tools & Technologies

- **Python**, **Pandas**, **NumPy**, **Matplotlib**
- **yfinance** for price data
- **Google Colab** + **Google Drive** (project environment)
- **Power BI** (for optional visualization)
- **GitHub** for version control
---
## 🧠 Strategy Logic

For each month from 2010 to 2024:

1. Compute 6-month return for each stock (skip the most recent month)
2. Rank all stocks by this momentum score
3. Select the **top 20 stocks**
4. Buy and hold them for 1 month
5. Repeat monthly

The strategy is benchmarked against **SPY (S&P 500 ETF)** for comparison.

---

## 📊 Performance Summary

| Metric              | Momentum Strategy | SPY (Benchmark) |
|---------------------|------------------:|----------------:|
| Annualized Return   |        Higher   |     Lower     |
| Volatility          |        Moderate    |     Lower       |
| Sharpe Ratio        |        > 1.0    |     < 1.0     |
| Max Drawdown        |        Higher      |     Lower       |

> ⚠️ This backtest does not include transaction costs or slippage.

---

## 📈 Sample Output

![Cumulative Returns](https://github.com/KlarenceKPIs/momentum-strategy/blob/main/momentum-strategy/results/momentum_vs_spy_chart.pngg)  
*Momentum strategy vs benchmark (SPY), 2010–2024*

---
## Disclaimer

This project is for educational purposes only. It is not financial advice. Historical performance does not guarantee future results.



### 1. **Newton's Interpolation Polynomial (S&P500)**

A web-based **Newton's Interpolation Polynomial** calculator built with **HTML**, **CSS**, and **JavaScript**. This tool performs interpolation on **S&P500 historical data** and allows users to input custom data points for financial analysis.

#### Demo:
Check out the live demo on [GitHub Pages](https://klarencekpis.github.io/Newton-s-Interpolating-Polynomial/).

- **Predefined Dataset:** Historical S&P500 data points (monthly closing prices).
- **User-defined Dataset:** Input your own data points for interpolation.
- **Features:** 
  - Real-time **S&P500 chart** visualization.
  - Display of the **Newton interpolation polynomial** and the result at a specific point.

#### Key Insights:
- Uses **S&P500** historical data as a foundation for interpolation.
- Can be applied to **market trend forecasting** or **missing data estimation** in financial datasets.
- **Interactive chart** for visual analysis of financial trends.

#### Source Code: [Source Code Repository](https://github.com/KlarenceKPIs/Newton-s-Interpolating-Polynomial)
---

## 🧰 Tools and Technologies:
- **Languages:** HTML, CSS, JavaScript
- **Financial Data:** **S&P500 Historical Data** (monthly closing prices)
- **Charting:** [TradingView Widget](https://www.tradingview.com/widget/) for S&P500 visualization
- **Methodology:** **Newton's Interpolation Polynomial**

---

## 🔗 More Projects Coming Soon!
