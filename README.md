#  Trader Behavior Analysis During Fear-Dominated Crypto Markets

This project explores the relationship between market sentiment and trader performance using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

# Objective

To analyze how market sentiment — especially fear — influences trading behavior, profitability, and risk across different cryptocurrencies. The project aims to uncover actionable insights that can help inform smarter trading strategies.

# Datasets Used

1. **Bitcoin Market Sentiment Dataset**
   - Columns: 'Timestamp`, `Classification` (e.g., Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
   - Source: Bitcoin Fear & Greed Index

2. **Historical Trader Data (Hyperliquid)**
   - Columns: 'Timestamp', 'Coin, 'Closed PnL','Execution Price`,`Size`, `Side`, `Leverage`, etc.
   - Contains over 211,000 trades

## 🔍 Key Analyses

- Cleaned and merged sentiment data with trade records
- Simplified sentiment into: **Fear**, **Greed**, **Neutral**
- Explored average and median profits on Fear days
- Identified top-performing coins under fear (e.g., AVAX, DOGE, SOL)
- Analyzed profit/loss ratios and volatility (std dev of PnL)
- Time-series plot of average trader PnL

## 📈 Key Insights

- Over **50% of trades on Fear days made no profit or loss**
- **Average PnL** was ₹48.75, but **standard deviation** was very high (~₹919), indicating high-risk trades
- **Few coins consistently outperformed** even in fearful markets
- High variance suggests speculative and high-stakes trading under fear conditions

## 📄 Files

- 'Trader_Performance_vs_Sentiment.ipynb 
- 'historical_data.csv` → Hyperliquid trade data
- 'fear_greed_index.csv` → Sentiment data

## ✅ Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub (for version control and presentation)
