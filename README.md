# 📊 Junior Data Scientist - Trader Behavior Insights

## Assignment Overview
This repository contains the completed data science assignment for the Web3 Trading Team, focused on analyzing the relationship between **trader behavior** (profitability, risk, volume, leverage) from Hyperliquid data and overall **Bitcoin Market Sentiment** (Fear vs. Greed). The goal is to uncover hidden trends that can inform smarter trading strategies.

The submission strictly adheres to the mandated submission format.

---

## 📁 Project Structure

The final directory structure is as follows:
---

## 💻 Setup and Access

All work was completed in **Google Colab notebooks**.

### 1. **Accessing the Code**

* **Primary Notebook (notebook_1.ipynb):** **[INSERT YOUR 'Anyone with the link can view' Colab URL]**

### 2. **Datasets**

The two primary datasets used are:
* **Historical Trader Data (Hyperliquid):** Columns include `account`, `execution price`, `closedPnL`, `leverage`, etc.
* **Bitcoin Market Sentiment (Fear & Greed Index):** Columns include `Date` and `Classification` (Fear / Greed).

### 3. **Methodology Highlights**

The core analysis involved a critical step: aligning the time-stamped Trader Data with the daily Sentiment Data via a common date key to tag each trade with the daily market sentiment.

---

## 📈 Key Visual Insights

The following visualizations illustrate the core findings presented in the `ds_report.pdf`.

### 1. Trade Profitability vs. Market Sentiment
This Box Plot compares the distribution of trade outcomes (`closedPnL`) when the market is in **Fear** versus **Greed**.

![Box Plot of closedPnL by Market Sentiment](outputs/image_251547.png)

### 2. Risk-Taking (Leverage) vs. Sentiment
This Bar Chart shows a clear divergence in risk appetite, indicating that traders take on significantly more leverage during certain sentiment phases.

![Bar Chart of Average Leverage Used by Market Sentiment](outputs/image_256702.png)

### 3. Trading Volume vs. Sentiment
This Bar Chart quantifies the total market participation, showing how overall liquidity and volume shift dramatically between the two sentiment classifications.

![Bar Chart of Total Trading Volume by Market Sentiment](outputs/image_256723.png)
