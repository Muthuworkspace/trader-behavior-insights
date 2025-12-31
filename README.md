Trader Behavior Insights Based on Market Sentiment

This repository contains the analysis for the Junior Data Scientist – Trader Behavior Insights assignment. The objective of this project is to explore how trader behavior and performance vary across different Bitcoin market sentiment regimes.

Project Structure :
    
    trader-behavior-insights/
    
    ├── notebook_1.ipynb

    ├── csv_files/
        │
    │   ├──merged_data.csv
    
    ├── outputs/
        │    
    │   ├── pnl_by_sentiment.png
        │    
    │   ├── risk_by_sentiment.png
        │    
    │   └── winrate_by_sentiment.png
    
    ├── ds_report.pdf
    
    └── README.md

Overview :
The analysis integrates two datasets:
Historical trader-level data containing trade details such as size, profit/loss, and timestamps.
A Bitcoin market sentiment index providing daily classifications such as Fear, Neutral, Greed, Extreme Fear, and Extreme Greed.
The datasets were aligned by date and analyzed to understand how sentiment influences trader risk-taking behavior, profitability, and accuracy.

Key Questions Addressed :
How does trader profitability vary across different market sentiment regimes?
Do traders take more risk during Fear or Greed?
Does trading accuracy change during emotionally extreme market conditions?

Methodology :
Loaded and cleaned both datasets.
Standardized timestamps and aligned records by date.
Merged trade data with daily sentiment labels.
Engineered behavioral features such as profitability indicators and risk proxies.
Conducted descriptive analysis and visualization to uncover behavioral patterns.

Results Summary :
The analysis shows that:
Profitability and win rates are highest during Extreme Greed.
Traders take larger risks during Fear, but without improved returns.
Trading accuracy deteriorates during Extreme Fear.
Neutral markets show weaker performance compared to emotionally charged regimes.
These findings suggest that sentiment plays a significant role in shaping trader behavior and can be incorporated into strategy and risk management frameworks.

How to Use :
Open notebook_1.ipynb to view the full analysis workflow.
Refer to ds_report.pdf for a detailed explanation of findings and interpretations.
View the plots in the outputs/ folder for visual insights.

Notes :
the original datasets are not included in this repository as they are publicly available from the sources provided in the assignment.

Author : 

Muthukumaresan V


