# 📊 Trader Performance Analysis Based on Market Sentiment (Fear & Greed Index)

## 📌 Project Overview

This project analyzes how trader performance changes under different market sentiment conditions using the Fear & Greed Index.

The objective is to:
- Understand how sentiment impacts profitability
- Compare high vs low position size traders
- Cluster traders based on behavior
- Generate actionable trading strategy insights

---

## 📂 Repository Structure


🧠 Methodology
1️⃣ Data Processing

Loaded historical trading data

Loaded Fear & Greed Index data

Converted timestamps to proper datetime format

Merged both datasets on date

2️⃣ Sentiment Classification

Used Fear & Greed Index value

Categorized into:

Extreme Fear

Fear

Neutral

Greed

Extreme Greed

3️⃣ Performance Metrics Computed

Total PnL

Average PnL

Trade Count

Win Rate

Average Position Size

4️⃣ Trader Segmentation

Used KMeans clustering on:

Average Closed PnL

Average Position Size

Trade Count

Average Sentiment Value

📊 Key Insights
🔹 Insight 1: High Size Traders Perform Better

High position size traders generated significantly higher average PnL compared to low size traders.

🔹 Insight 2: Performance Varies by Sentiment

Traders take larger positions during Fear periods.

Extreme Greed shows relatively lower position sizing.

Risk appetite increases during uncertain market phases.

🔹 Insight 3: Clustering Reveals Trader Types

Clustering identified:

Aggressive high-volume traders

Moderate consistent traders

Low-volume conservative traders

📈 Strategy Recommendations
✅ Strategy 1: Increase Position Size During Fear (With Risk Control)

Data shows higher profitability during fear-driven markets.

✅ Strategy 2: Reduce Aggression During Extreme Greed

Markets tend to be overheated during extreme greed — lower risk exposure recommended.

✅ Strategy 3: Follow High-Performing Trader Clusters

Cluster analysis helps identify profitable trader behavior patterns.

📌 Output Charts Included

Average PnL: High vs Low Size Traders

Average Position Size by Sentiment

Cluster Performance Comparison

Sentiment Summary Table

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Scikit-Learn (KMeans Clustering)

📎 Conclusion

This analysis demonstrates that market sentiment significantly impacts trader behavior and profitability.

By combining sentiment indicators with trader performance metrics, we can design smarter and more adaptive trading strategies.

---

# ✅ What To Upload To GitHub

Upload:

- ✅ `Task.ipynb`
- ✅ `README.md`
- ✅ CSV files (if allowed)
- ✅ Screenshot images (optional but good)
- ✅ Output charts (optional folder)

---

# 🔥 Final Tip

After uploading:

- Add description in repo settings:
  
