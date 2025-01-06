### Moving Average Convergence Divergence

**What is Moving Average Convergence Divergence(MACD)?**

**Moving Average Convergence Divergence** is a popular technical indicator used in trading to identify trends, momentum and potential reversals in price movements. developed by Gerald Appel, it uses exponential moving averages (EMAs) of prices to reveal changes in strength, direction, and duration of a trend.

**Components of MACD**

1. **MACD Line:**
    - The MACD line is the difference between two exponential moving averages (EMAs) of the clossing price :

    $$
    \text{MACD Line} = EMA_{Short} - EMA_{Long}
    $$

    - Common default values:
        - Short EMA = 12-period EMA
        - Long EMA = 26-period EMA

2. **Signal Line:**
    - A 9-period EMA of the MACD line:

    $$
    \text{Signal Line} = EMA_{9}\left(\text{MACD Line}\right)
    $$

    - This line smooths the MACD line and helps identify buy or sell signals.

3. **MACD Histogram:**
    - The difference between the MACD line and the signal line:

    $$
    MACD Histogram = MACD Line - Signal Line
    $$

    - The histogram visually represents the strength and direction of the momentum.

**How to Interpret MACD?**

1. **Crossover Signals:**
    - **Bullish Crossover:**
        - Occurs when the MACD line crosses above the Signal Line.
        - Indicates a potential upward price movement.
    - **Bearish Crossover:**
        - Occurs when the MACD line crosses below the Signal Line.
        - Indicates a potential downward price movement.

2. **Zero Line Crosses:**
    - When the MACD line crosses above the zero line, it suggests that the short-term EMA is now greater than the long-term EMA, signaling upward momentum.
    - Conversly, crossing below the zero line suggests downward momentum.

3. **MACD Histogram:**
    - A growing histogram indicates increasing momentum in the direction of the crossover.
    - A shrinking histogram suggests weakening momentum.

4. **Divergence:**
    - **Bullish Divergence:**
        - Price makes lower lows, but MACD makes higher lows.
        - Suggests potential reversal to the upside.
    - **Bearish Divergence:**
        - Price makes higher highs, but MACD makes lower highs.
        - Suggests potential reversal to the downside.

**Formula for MACD:**

1. **Compute the MACD Line:**

$$
    \text{MACD Line} = EMA_{12} - EMA_{9}
$$

2. **Calculate the Signal Line:**
- Apply a 9-period EMA to the MACD Line:

$$
\text{Signal Line} = EMA_{9} \left(\text{MACD Line} \right)
$$

4. **Compute the MACD Histogram**:

$$
\text{MACD Histogram} = \text{MACD Line} - \text{Signal Line}
$$