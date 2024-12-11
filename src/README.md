## Dataset for Portfolio Optimization using PCA

Historical Financial data of multiple assets

### Asset Classes within Portfolio:

### 1. Stocks

    - AMD
    - Tesla
    - Boeing
    - S&P500

### Stocks Features

| **Feature Name**                             | **Description**                                                                                                               |
| -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Price Returns                                | The percentage change in the asset price over a given period (e.g., daily, weekly). Important for capturing price volatility. |
| Log Returns                                  | The logarithmic change in asset price. It normalizes the data and is often preferred in financial analysis.                   |
| Volatility (Standard Deviation)              | Measures the degree of price variation over a certain period, showing the asset's risk.                                       |
| Moving Average (MA)                          | The average of an asset’s price over a specific period (e.g., 50-day MA, 200-day MA), indicating long-term trend.             |
| Relative Strength Index (RSI)                | Momentum oscillator to measure the speed and change of price movements, indicating overbought or oversold conditions.         |
| Moving Average Convergence Divergence (MACD) | A trend-following momentum indicator showing the relationship between two moving averages of an asset’s price.                |
| Beta                                         | Measures the asset's sensitivity to overall market movements, indicating its systemic risk compared to the market.            |
| Sharpe Ratio                                 | Measures the return per unit of risk. A higher Sharpe ratio indicates better risk-adjusted performance.                       |
| Maximum Drawdown                             | The largest peak-to-trough drop in the asset’s price, highlighting the worst-case scenario for investors.                     |
| Price-to-Earnings Ratio (P/E)                | Measures the asset’s valuation by comparing its current price to its earnings.                                                |
| Dividend Yield                               | Represents the annual dividend income relative to the stock price, indicating income-generating potential.                    |

### 2. Bonds

    - Apple Bonds (One of the most financially stable company)
    - Microsoft Bonds (Tech giant with robust financials)
    - US Treasury Bonds (One of the safest investment globally)

### Bonds Features

| **Feature Name**          | **Description**                                                                                                                       |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Yield to Maturity (YTM)   | The total return anticipated on a bond if held until it matures, considering the bond’s current price, coupon payments, and maturity. |
| Duration                  | Measures the bond's price sensitivity to interest rate changes. A higher duration indicates higher price sensitivity.                 |
| Credit Spread             | The difference in yield between a corporate bond and a government bond of similar maturity, reflecting credit risk.                   |
| Bond Convexity            | Measures the bond's price sensitivity to interest rate changes, considering the bond’s curvature.                                     |
| Interest Rate Sensitivity | A measure of how much a bond’s price will fluctuate with changes in interest rates, useful for managing rate risk.                    |
| Coupon Rate               | The fixed interest rate paid by the bond issuer to the bondholder, providing insight into income generation.                          |
| Spread to Benchmark       | The difference between the bond's yield and the yield of a benchmark bond (e.g., 10-year Treasury bond), indicating relative risk.    |
| Credit Rating             | A measure of a bond’s credit risk, with higher ratings indicating lower risk. Common ratings include AAA, BBB, etc.                   |

### 3. Commodities

    - Gold (Safe Haven asset, esp. during market volatility)
    - Crude Oil (highly volatile due to geopolitical events)
    - Copper (widespread use in construction, electronics & manufacturing)

### Commodities Features

| **Feature Name**                | **Description**                                                                                                                                    |
| ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Price Returns                   | The percentage change in the commodity price over a specified period, representing price volatility.                                               |
| Log Returns                     | The logarithmic change in commodity price, preferred for normalizing price data and financial analysis.                                            |
| Volatility (Standard Deviation) | Measures the variability in commodity prices over a set period, indicating the risk of the commodity.                                              |
| Commodity Index                 | A composite index (e.g., S&P GSCI) that tracks a basket of commodities, giving a broad view of the commodity sector.                               |
| Seasonality Index               | Measures price fluctuations based on the time of year (e.g., higher agricultural prices during certain seasons).                                   |
| Open Interest                   | The total number of outstanding contracts in a futures market, indicating market interest and liquidity.                                           |
| Inventory Levels                | Tracks the supply of commodities (e.g., oil inventories), affecting commodity price movements due to supply-demand dynamics.                       |
| Forward Curve                   | The price structure of commodity futures, showing whether the commodity is in backwardation or contango.                                           |
| Rolling Correlation             | Measures the correlation between the commodity and other asset classes (stocks, bonds) over a rolling window, useful for diversification analysis. |
| Geopolitical Risk Factor        | Assesses the potential impact of geopolitical events (e.g., wars, sanctions) on commodity prices.                                                  |
| Currency Impact (FX)            | Measures the impact of currency fluctuations (e.g., USD fluctuations) on commodity prices, especially important for dollar-denominated assets.     |
