### Average True Range

**What is ATR?**

Average True Range is a technical indicator that measures market volatility. It is widely used in trading to gauge the degree of price movement in a stock. Unlike other indicators, the ATR does not indicate the price direction but rather the degree of price fluctuation, making it useful in identifying volatility trends.

It calculates the average range of a price movement over a specific period, typically 14 periods.

**Average True Range Formula:**

The ATR is a moving average of the True Ranges (TR) over a specified number of periods:

$$
\text{ATR} = \frac{\sum_{i=1}^n TR_i}{n}
$$

Where:
- $TR_i$: True Range for each period i.
- $\text{n}$: Number of periods (e.g. 14)

**Why is ATR Useful?**

1. **Volatility Measurement:**
    - ATR reflects market volatility wihtout considering price direction.
    - **High ATR:** Indicates strong price movement (high volatility).
    - **Low ATR:** Suggests minimal price movement (low volatitlity).

2. **Setting Stop-Loss Levels:**
    - ATR helps traders set stop-loss levels dynamically based on market conditions.
    - **Example:** A trader my set a stop-loss at 1.5 X ATR below the entry price in volatility markets to avoid premature exists.

**Using ATR in Trading Strategies:**
1. **Trailing Stop-Loss:**
    - Use ATR to set stop-loss levels that adapt to volatility.
    - If the ATR is 2 and a stock is trading at $100:
        - Set a stop-loss at 100−2×ATR=96.
2. **Detecting Breakouts:**
    - When ATR spikes from a low value, it often signals the beginning of a significant price movement.