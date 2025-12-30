```markdown
# 📈 Data Science Assignment – Trader Behavior & Market Sentiment Analysis


## 📌 Project Overview

This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader behavior/performance** using historical trading data from **Hyperliquid**.
The goal is to uncover patterns in **profitability, risk-taking, leverage usage, and trading volume** under different market sentiment conditions and derive insights that can support **smarter trading strategies**.

---

## 📂 Datasets Used

### 1️⃣ Bitcoin Market Sentiment Dataset

* **Columns:** `Date`, `Classification` (Fear / Greed)
* Represents overall market psychology on a daily basis.

### 2️⃣ Historical Trader Data (Hyperliquid)

* **Columns include:** `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.
* Provides detailed trade-level information for performance and behavior analysis.

---

## 🎯 Objective

* Analyze how trader behavior changes during **Fear vs Greed** market conditions.
* Evaluate differences in:

  * Profit & Loss (PnL)
  * Leverage usage
  * Trade size and volume
  * Risk-taking behavior
* Identify hidden trends that can influence **data-driven trading decisions**.

---

## 🧠 Key Analysis Steps

1. Data loading and preprocessing
2. Data cleaning and type conversions
3. Merging trader data with sentiment data by date
4. Exploratory Data Analysis (EDA)
5. Visualization of trader behavior under Fear vs Greed
6. Interpretation of results and insights

All analysis is performed using **Google Colab notebooks**.

---

## 📊 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Google Colab

---

## 📁 Project Structure

```
ds_usha/
├── notebook_1.ipynb        # Main analysis notebook (Google Colab)
├── csv_files/              # Raw and processed datasets
├── outputs/                # Saved visualizations and charts
├── ds_report.pdf           # Final summarized insights and conclusions
└── README.md               # Project documentation
```

---

## 📈 Key Insights (Summary)

* Trader profitability and risk appetite vary significantly between **Fear** and **Greed** market phases.
* Higher leverage and aggressive positions are more common during **Greed** periods.
* Fear-driven markets tend to show reduced trade sizes and more conservative behavior.
* Market sentiment acts as a strong contextual signal for understanding trader performance.

*(Detailed findings are available in `ds_report.pdf`.)*

---

## 📌 Conclusion

This project demonstrates how combining **market sentiment data** with **historical trading data** can uncover meaningful behavioral patterns. Such insights can be valuable for **risk management**, **strategy optimization**, and **decision-making** in crypto trading environments.

---

## 👤 Author

**Usha Mandapalli**
Aspiring Data Scientist | Analytics Enthusiast

---

