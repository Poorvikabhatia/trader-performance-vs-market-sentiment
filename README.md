# Trader Performance vs Market Sentiment Analysis

## Primetrade.ai — Data Science Intern Round-0 Assignment

### Objective
The objective of this project is to analyze how Bitcoin market sentiment (Fear/Greed Index) affects trader behavior and trading performance on Hyperliquid.

The analysis focuses on:
- Trader profitability (PnL)
- Trading activity
- Trade sizes
- Long vs Short behavior
- Market sentiment impact on decision-making

---

# Datasets Used

## 1. Bitcoin Fear & Greed Dataset
Contains:
- Date
- Fear/Greed classification
- Sentiment value

## 2. Hyperliquid Historical Trader Dataset
Contains:
- Trader account details
- Trade execution information
- Trade size
- Position direction
- Closed PnL
- Timestamp information

---

# Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

---

# Project Workflow

## 1. Data Loading
Both datasets were loaded into Google Colab using Pandas.

## 2. Data Cleaning
Performed:
- Missing value checks
- Duplicate record checks
- Datetime conversion
- Numeric datatype conversion

## 3. Dataset Merging
Datasets were merged using a common daily date column to align trader activity with market sentiment.

## 4. Feature Engineering
Created analytical metrics such as:
- Daily PnL
- Trade frequency
- Average trade size
- Long vs Short distribution
- Trader profitability segments

## 5. Data Visualization
Used:
- Boxplots
- Bar charts
- Comparative visualizations

to identify behavioral patterns under different market conditions.

---

# Key Insights

## Insight 1
Trading activity increased significantly during Greed and Extreme Greed market conditions.

## Insight 2
Average trade sizes were generally larger during Greed periods, indicating higher trader confidence and risk-taking behavior.

## Insight 3
Long positions were more dominant during positive market sentiment conditions.

## Insight 4
Fear market conditions showed comparatively cautious trading behavior and reduced market participation.

## Insight 5
Profitable traders generally executed larger trades compared to loss-making traders.

---

# Strategy Recommendations

## Strategy 1 — Reduce Risk During Fear
During Fear periods, traders should reduce position sizes and avoid excessive risk exposure.

## Strategy 2 — Momentum-Based Trading During Greed
Greed and Extreme Greed periods may favor momentum-based strategies because of increased market participation.

## Strategy 3 — Strong Risk Management
Larger trade sizes should always be combined with strict stop-loss and position management strategies.

---

# How to Run the Project

## Step 1
Open the notebook in Google Colab or Jupyter Notebook.

## Step 2
Install required libraries if needed:

```python
pip install pandas numpy matplotlib seaborn
```

## Step 3
Place datasets in the appropriate directory.

## Step 4
Run all notebook cells sequentially.

---

# Files Included

- `trader_sentiment_analysis.ipynb`
- `README.md`
- `insights.md`
- `fear_greed_index.csv`
- `historical_data.csv`

---

# Dataset Note

The historical trader dataset was not uploaded to GitHub due to GitHub file size limitations.

The analysis was performed using the original dataset provided in the assignment.

---

# Conclusion

This project demonstrates that market sentiment significantly influences trader behavior, trading activity, and positioning decisions.

The findings can help design:
- sentiment-aware trading strategies
- improved risk management systems
- trader behavior monitoring frameworks
