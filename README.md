<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# **Sharpe and Sortino Ratios**

#### Calculation and comparison between two important risk metrics: Sharpe and Sortino

---

Before selecting a financial asset, investors should consider the risk-adjusted return rather than just the simple return. This raises the question: which index is more appropriate for measuring this risk-adjusted return? The Sharpe Ratio or the Sortino Ratio? And how are these indices related?

The Sharpe Ratio and the Sortino Ratio are metrics used to evaluate the risk-adjusted return of investments. The Sharpe Ratio assesses an investment's performance relative to a risk-free asset, taking into account total volatility. The Sortino Ratio, on the other hand, is a variation of the Sharpe Ratio that only considers negative risk or downside volatility.

## Methodology

1. **Installation and Import of Libraries**  
   Libraries such as `quantstats`, `yfinance`, and `plotly` are used for financial data analysis and visualization.

2. **Data Acquisition**  
   Closing price data for BTC-USD is downloaded and analyzed to calculate the indices.

3. **Metrics Analysis**  
   The Sharpe Ratio and the Sortino Ratio are calculated using a risk-free rate of 5% per semester. The indices are then correlated and visualized to understand their relationship.

4. **Insights from Correlation**  
   - **Consistency in Risk Assessment**: The high correlation suggests that both indices often provide a similar view of the balance between return and risk.
   - **Focus on Negative Volatility**: The Sortino Ratio focuses on negative volatility, which can be useful for conservative strategies.
   - **Decision on Which Index to Use**: The choice between indices may depend on the investor's objective, whether it is to understand overall risk-adjusted performance (Sharpe) or to minimize significant devaluation risks (Sortino).

The analysis reveals that, despite the high correlation between the Sharpe and Sortino Ratios, each offers a distinct perspective that may be more suitable depending on investment goals and strategies.

---



[<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>](https://colab.research.google.com/github/GeorgeTelles/sharpe_sortino_ratio/blob/main/Sharpe_Sortino_Ratio.ipynb)

<img src="https://github.com/GeorgeTelles/sharpe_sortino_ratio/blob/ed9bd99e67bb5397f1789f5673d2c69b9a8ccfbe/sharpe%20vs%20sortino.png" alt="Sharpe and Sortino"/>
