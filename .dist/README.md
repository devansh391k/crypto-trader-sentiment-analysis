# Trader Behavior Analysis Using Bitcoin Market Sentiment

## Objective
This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data and the Fear & Greed Index.

## Datasets Used
1. Bitcoin Fear & Greed Index Dataset
2. Historical Trader Data from Hyperliquid

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Analysis Performed
- Data Cleaning
- Data Merging
- Sentiment-Based Profitability Analysis
- Buy vs Sell Performance Analysis
- Trade Count Analysis
- PnL Distribution Analysis
- Correlation Heatmap
- Daily PnL Analysis
- Trades Per Day Analysis
- Long vs Short Ratio Analysis
- Trader Segmentation

## Key Insights

- Traders achieved higher average profits during Greed sentiment.
- Trading activity was highest during Fear markets.
- SELL trades performed strongly during Greed conditions.
- Fear markets showed the highest volatility in profits and losses.
- Trade size and transaction fees showed strong positive correlation.

## Strategy Recommendations

1. During Fear periods, traders should reduce position sizes because profit variability is higher.

2. During Greed periods, traders with consistently high win rates may increase trading frequency while maintaining disciplined risk management.

## Dataset Limitation

The provided dataset does not include leverage information. Therefore, trade exposure was approximated using the **Size USD** feature for segmentation and behavioral analysis.

## Conclusion

Market sentiment significantly influences trader behavior, profitability, and trading activity. Incorporating sentiment-aware trading strategies can improve risk management and overall trading performance.