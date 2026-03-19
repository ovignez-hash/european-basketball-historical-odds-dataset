# 🏀 The "Bookmaker Brain" Database: EUROPEAN BASKETBALL & FIBA (Free Sample)
====================================================================

**🛑 Stop wasting weeks on Data Engineering and Web Scraping. Start Backtesting immediately.**

The European Basketball betting market (Euroleague, Eurocup, FIBA domestic leagues) is one of the most inefficient sports betting markets in the world, offering significant Alpha for quantitative models. However, building a clean, historical dataset for these leagues is a nightmare due to constant sponsor naming changes, COVID-19 administrative anomalies, and fragmented data sources.

This Master Dataset solves the Data Engineering problem entirely. It has been manually extracted, cleaned, and perfectly uniformized to provide institutional-grade data for Quants, Data Scientists, and Professional Betting Syndicates.

---
## ⚠️ ABOUT THIS REPOSITORY (50-ROW FREE SAMPLE)

This repository contains a **FREE 50-MATCH SAMPLE**. It allows Data Scientists, Quants, and Betting Syndicates to test the ultimate European Basketball & FIBA Historical Dataset. Import this into your Python/Pandas environment and see the engineering quality for yourself.

---
## 🚀 SCALE UP: THE FULL 15-YEAR MASTER DATASET (Available on Gumroad)

50 rows are not enough to train a robust Machine Learning algorithm. Due to the massive engineering effort (72+ hours of manual extraction and cleaning), the complete historical Master File is hosted externally.

**📊 The Numbers:**
*   **Volume:** 63,290 perfectly formatted matches.
*   **Depth:** 15+ years of historical data (2008 to 2026).
*   **Coverage:** Euroleague, Eurocup, Champions League, Liga ACB (Spain), Lega A (Italy), Super Lig (Turkey), BBL (Germany), Betclic Elite (France), NBL (Australia), and more.

👉 **[DOWNLOAD THE FULL 63,290 ROWS DATASET HERE](https://sportsdataolivier.gumroad.com/l/hswnlg)**

---
## 💎 KEY PREMIUM FEATURES (Why this dataset is unique)

*   **100% Primary Key Uniformity:** Team names are perfectly standardized across all 15 years. Whether "Anadolu Efes" or "Baskonia" plays in their domestic league or Euroleague, the naming remains identical despite historical sponsor changes. Zero data mapping required. Your algorithms will never break.
*   **Target Variables Pre-Calculated:** Includes ready-to-use columns for Machine Learning: `End_Of_RT` (Outcome at the end of regulatory time, crucial for specific bookmaker rules), `Number of Points - TOTAL`, `Number of Points - INTERVAL`, and `Winning Margin`.
*   **Data Quality Transparency:** Unlike automated scrapers, this dataset accounts for historical federative decisions (e.g., The 2019/2020 Serie A2 Italian season was completely cancelled and purged by the Federation due to the pandemic outbreak. This dataset respects this historical reality).

---
## 💻 QUICKSTART (Python/Pandas)

Test this sample right now in your environment to verify the data integrity:

```python
import pandas as pd

# Load the free technical sample (Verify the filename matches your download)
df = pd.read_csv('Sample_European_Basketball_and_Australia.csv')

# Prove the data is ML-Ready (Zero missing closing odds)
print("Total missing values:", df.isnull().sum().sum())

# Display the market truth and pre-calculated variables
print(df.head())
```
---
🛡️ DATA TRANSPARENCY & QUALITY GUARANTEE
Aggregating decades of historical sports data involves merging thousands of rows from widely disparate legacy formats and archived sources. While rigorous manual processing and data engineering have been applied to clean, structure, and consolidate this vault, I guarantee a data completeness of >99.9%. Missing dates and corrupted odds have been aggressively filtered to ensure this dataset is immediately usable in your Machine Learning pipelines.
---

---
⚖️ LEGAL DISCLAIMER & TERMS OF USE
This dataset is provided for data science, backtesting, and research purposes only. It does not constitute financial or betting advice.
Past performance is not indicative of future results. The creator of this dataset is not responsible for any financial losses incurred through sports betting or trading based on the models built with this data.
Resale, redistribution, or unauthorized sharing of this dataset is strictly prohibited.
Good luck with your modeling, Olivier Sports Data
---


