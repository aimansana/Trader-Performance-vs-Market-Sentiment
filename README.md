# Crypto Market Sentiment and Trader Behaviour Analysis

## Project Overview

This project explores the relationship between cryptocurrency market sentiment and trader behaviour using the Bitcoin Fear & Greed Index and historical trading data.

The analysis examines how different market sentiment conditions, ranging from Fear to Greed, relate to trading activity, profitability, and trading patterns.

## Objectives

- Analyse the relationship between market sentiment and trader behaviour.
- Identify trading patterns across different sentiment categories.
- Compare profitability and trading activity under different market conditions.
- Examine differences in long and short trading positions.

## Datasets

The project uses two datasets:

1. **Fear & Greed Index:** Contains historical market sentiment values and classifications.
2. **Historical Trading Data:** Contains trader-level transaction details, including account information, execution prices, trade sizes, direction, and closed PnL.

## Analysis Performed

- Data cleaning and preprocessing, including missing value and duplicate checks.
- Conversion and standardisation of timestamp data.
- Merging datasets based on trading dates.
- Sentiment-based analysis of trading activity.
- Account-wise and date-wise analysis.
- Comparison of long and short trading positions.
- Calculation and analysis of:
  - Win rates
  - Average trade size
  - Average and total PnL
  - Number of trades
  - Long-short ratios
- Analysis of PnL and trading activity across sentiment categories.

## Visualisations

### Trading Activity and Market Sentiment

<!-- Add visualisation here -->

### Profitability Analysis

<!-- Add visualisation here -->

### Sentiment-Based Comparisons

<!-- Add visualisation here -->

### Additional Analysis

<!-- Add visualisation here -->

## Key Findings

<!-- Add your key findings and observations here after finalising the analysis. -->

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
Crypto-Market-Sentiment-Analysis/
│
├── data/
│   ├── fear_greed_index.csv
│   └── historical_data.csv
│
├── images/
│   └── (Project screenshots and visualisations)
│
├── analysis.ipynb
│
└── README.md
```

## Conclusion

This project uses historical cryptocurrency market data to investigate how market sentiment relates to trader behaviour, trading activity, and profitability. It applies data preprocessing, exploratory data analysis, and visualisation techniques to identify patterns across different market conditions.

---

**Note:** This project is for educational and analytical purposes and does not constitute financial advice.
