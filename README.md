# Market-Sentiment-Impact-on-Trader-performance
Sentiment • Leverage • Strategy Insights

### Overview
This project analyzes how market sentiment (Fear & Greed Index) impacts trader performance using real trading data from Hyperliquid.

The goal is to uncover:
 - How sentiment affects profitability
 - The impact of leverage on risk and return
 - Behavioral patterns of successful traders
 - Data-driven strategies for smarter trading
###  Objectives
-  Analyze trader performance across sentiment phases
-  Evaluate leverage vs profitability trade-off
-  Compare long vs short strategies
-  Identify top trader behavior
-  alidate findings using statistical testing
### Dataset
1. Bitcoin Market Sentiment Dataset
- Date
- Classification (Extreme Fear → Extreme Greed)
2. Historical Trader Data (Hyperliquid)
- Account
- Execution Price
- Size (USD)
- Side (Buy/Sell)
- Closed PnL
- Timestamp
- Start Position
### Data Processing
- Cleaned and standardized timestamps
- Merged sentiment with trade data
- Handled missing & infinite values
- Created new features:
### Feature Engineering
- ROI → Profitability per trade
- win_flag → Profit/Loss indicator
- is_long → Trade direction
- approx_leverage → Risk exposure
- leverage_bucket → Categorized leverage levels
### Key Insights
- Market Sentiment
Extreme Greed → Highest profit & win rate
Extreme Fear → Lowest performance
- Leverage Behavior
Moderate leverage → Highest profitability
Low leverage → Higher win rate but lower returns
Extreme leverage → High risk, unstable outcomes
- Trade Direction
Short trades outperform long trades
Higher profitability + higher win rate
- Trade Activity
Most trading occurs during Fear
Best performance occurs during Greed

- Indicates overtrading in uncertain markets

### Top Traders
 - Consistently outperform average traders
- Better risk management
- Smarter trade execution
- Strong performance across all market conditions
### Statistical Validation
- Analysis	Test	Result
- Sentiment vs PnL	ANOVA	 Significant
- Leverage vs PnL	ANOVA	   Significant
- Long vs Short	T-test	   Significant

- Insights are statistically validated and not due to randomness.
### Dashboard
Built using Power BI Desktop
Includes:
 - KPI overview (PnL, Win Rate, Trades)
 - Sentiment analysis
 - Leverage behavior
 - Long vs Short comparison
 - Trade activity trends
 - Top traders leaderboard

 - <img width="400" height="250" alt="Screenshot (1260)" src="https://github.com/user-attachments/assets/e576c57f-079e-4fa5-ade9-d5b4cae5ccce" />


### Tech Stack
Python (Pandas, NumPy)
Data Visualization (Matplotlib, Seaborn)
Statistical Testing (SciPy)
Power BI

### Key Takeaway
Trader success is driven by timing, disciplined leverage, and strategy — not just trading activity.

### Future Improvements
- Predictive modeling (churn / profitability)
- Time-series forecasting
- Real-time dashboard integration

