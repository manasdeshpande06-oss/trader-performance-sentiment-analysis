# Project Summary

## Methodology

1. Loaded and explored the Fear & Greed and Hyperliquid trader datasets.
2. Checked for missing values and duplicate records.
3. Converted timestamps and aligned both datasets using daily dates.
4. Merged sentiment data with trader activity data.
5. Calculated key metrics including:

   * Average PnL
   * Trade Frequency
   * Average Trade Size
   * Long/Short Distribution
6. Segmented traders based on:

   * Trading Frequency
   * Position Size
   * Profitability

## Key Insights

### Insight 1: Greed Periods Produce Higher Profitability

Average profit per trade was highest during Greed periods (87.89), compared to Fear periods (50.05). This suggests traders perform better during optimistic market conditions.

### Insight 2: Fear Periods Generate Higher Trading Activity

Fear periods accounted for 133,871 trades, significantly higher than all other sentiment categories. This indicates increased trader activity during uncertain market conditions.

### Insight 3: Position Sizes Increase During Strong Emotional States

Average trade sizes were highest during Extreme Greed and Fear periods, indicating that traders tend to take larger risks when market emotions are strongest.

### Insight 4: Frequent Traders Outperform Infrequent Traders

Frequent traders achieved average profits of 496,528 compared to 147,032 for infrequent traders.

### Insight 5: Large Position Traders Earn Higher Profits

Traders with larger average position sizes generated higher average profitability than small-position traders.

## Strategy Recommendations

### Recommendation 1

Increase exposure during Greed periods while maintaining strict risk controls.

### Recommendation 2

Avoid excessive trading during Fear periods and focus only on high-conviction setups.

### Recommendation 3

Optimize position sizing, as larger-position traders achieved higher profitability in the dataset.

## Limitations

Leverage analysis could not be performed because leverage information was not available in the provided dataset.
