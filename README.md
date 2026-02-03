# Trader Behavior vs Market Sentiment Analysis

**Role:** Junior Data Scientist – Trader Behavior Insights  
**Candidate:** Anita Yadav  

---

## Project Overview
This project analyzes how trader behavior varies under different Bitcoin market sentiment
regimes (Fear vs Greed). By combining historical trader-level execution data with the
Bitcoin Fear & Greed Index, the objective is to identify patterns in profitability,
risk exposure, and trading activity.

The insights derived from this analysis aim to support more informed,
data-driven trading strategies.

---

## Dataset Description

### 1. Historical Trader Data
This dataset contains execution-level trading records, including:
- Account identifiers
- Execution price
- Trade size (tokens and USD)
- Trade direction (Buy / Sell)
- Realized profit and loss (PnL)
- Timestamps and transaction metadata

---

### 2. Bitcoin Fear & Greed Index
This dataset provides a daily market sentiment indicator based on market conditions.
Sentiment categories were normalized into:
- **Fear**
- **Greed**

to enable consistent behavioral comparison.

---

## Methodology
1. Cleaned and standardized raw datasets  
2. Extracted trade dates and aligned them with daily sentiment data  
3. Engineered key analytical features:
   - Trade profitability (win/loss)
   - Trade value as a proxy for trading volume
   - Risk exposure using trade size (USD) as a proxy  
4. Conducted exploratory data analysis (EDA) to compare trader behavior
   across different sentiment regimes  

---

## Key Findings
- Traders tend to exhibit higher win rates during Fear sentiment regimes  
- Greed regimes are associated with increased trading activity and higher risk exposure  
- Average trade sizes increase during Greed phases, indicating elevated risk-taking  
- Market sentiment plays a meaningful role in influencing trading behavior  

---

## Visual Outputs
All visualizations generated during the analysis are stored in the `outputs/` directory,
including:
- Average PnL by market sentiment  
- Win rate comparison across sentiment regimes  
- Risk exposure trends using trade size  
- Trading volume distribution by sentiment  

---


