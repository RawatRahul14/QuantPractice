## Garman-Klass Volatility

**What is Garman Klass Volatility?**

Garman-Klass Volatility is a measure of the volatility of a financial assets's price over a specific time period (In the codes, It is taken for a day). It improves on the basic measures of volatility by using high, low, opening and closing prices of the asset within a trading period. This measure is particularly suited for markets where price fluctuations during the day contain valuable information.

**Why is it useful?**

Traditional volatility calculations, such as those based only on the closing prices, may miss valuable intraday price information. Garman-Klass takes into account the day's high and low prices, which provides a more precise measure of true price variability.

**TheGarman-Klass Formula:**

The formula for Garman-Klass volatility is:

$$
\sigma^2 = \frac{1}{n} \sum_{t=1}^n \left[ \frac{1}{2} \left( \ln\left(\frac{H_t}{L_t}\right) \right)^2 - \left( 2\ln(2) - 1 \right) \left( \ln\left(\frac{C_t}{O_t}\right) \right)^2 \right]
$$

where:
- $\text{H}_t$: High price of the asset on day $\text{t}$.
- $\text{L}_t$: Low price of the asset on day $\text{t}$.
- $\text{C}_t$: Closing price of the asset on day $\text{t}$.
- $\text{O}_t$: Opening price of the asset on day $\text{t}$.
- $\text{n}$: Number of periods (e.g., days).
- $\sigma^2$: Variance (volatility squared).

**How is the Formula Derived?**
- Base Assumption:
    - Prices follow a geometric Brownian motion, where the logarithmic prices are normally distributed.

- Using High and Low Prices:
    - High and low prices within a day reflect the range of price movements. The log of their ratio is used as it is scale-invariant and suitable for percentage changes.

- Using Open and Close Prices:
    - Opening and closing prices reflect the start and end of the day's trading session. Their relationship helps refine the volatility estimate.
- Adjustment Factor:
    - The term $2\ln(2) - 1 \approx 0.386$ corrects for the overlapping information between high-low and open-close price ranges.