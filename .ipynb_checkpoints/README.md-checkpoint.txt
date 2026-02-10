# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and profitability.

## Files
- Trader_Sentiment_Analysis.ipynb → Main notebook
- fear_greed_index.csv → Sentiment dataset
- historical_data.csv → Trader dataset

## Methodology
- Cleaned and merged datasets by date
- Created metrics: PnL, win rate, trade frequency, position size
- Compared Fear vs Greed performance
- Segmented traders

## Key Insights
- High position traders suffer more losses during Fear markets
- Trading activity and profitability increase during Greed sentiment
- Low position traders show stable performance

## Strategy Recommendations
- Reduce position size during Fear markets
- Increase trade activity during Greed sentiment
- Use moderate position sizing for stable returns

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
