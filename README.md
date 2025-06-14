
---

## 📊 Google Colab Analysis Includes

- ✅ Data Cleaning & Preprocessing
- 📈 Time Series Plot of Closing Prices
- 📌 Daily Percentage Change Calculations
- 🧠 K-Means Clustering on Volatility Features
- 🎯 Evaluation using Silhouette Score, Davies-Bouldin, Calinski-Harabasz Index
- 📉 Feature Engineering for Power BI:  
  - `High_Low_Ratio`, `Is_Close_Higher_Than_Open`, etc.

---

## 📊 Power BI Dashboard Features

> **Total of 10+ powerful, interactive visuals**, including:

1. 📈 **Multi-Line Chart** – Compare multiple stock indices over time  
2. 📉 **Candlestick Chart** – Visualize OHLC price action  
3. 🔥 **Heatmap** – Correlation between indices  
4. 🧠 **Decomposition Tree** – Predict close > open based on other features  
5. 📊 **Clustered Bar** – Day-wise or Month-wise price movements  
6. 📆 **Slicer/Filter Controls** – Filter by Date, Index, or Range  
7. 📍 **Map (Optional)** – Index origin country  
8. 🔄 **Play-Axis Scatter Plot** – Animated time-based analysis  
9. 🔗 **Interlinked Tooltips** – Volume + Price insights  
10. 📊 **Donut/Pie Charts** – Distribution of increase/decrease days

---

## 📌 Key Insights

- NSEI and IXIC showed highest volatility in specific months
- Strong correlation between IXIC and GDAXI over time
- Most stocks have a 60%+ probability of closing higher than opening in certain quarters

---

## 🚀 How to Run

### ▶️ Google Colab
- Open `colab_notebook/stock_analysis_google_colab.ipynb`
- Upload the CSV from `data/`
- Run all cells to replicate the analysis

### 💼 Power BI
- Open `powerbi_dashboard/stock_dashboard.pbix`
- Refresh the dataset path to link it with `data/ebea2182-stock-dataset.csv`
- Explore visuals and filters interactively

---

## 📚 Future Work

- Implement LSTM for stock price prediction
- Add real-time market data using APIs (like Alpha Vantage or Yahoo Finance)
- Publish dashboard to Power BI cloud for online access
