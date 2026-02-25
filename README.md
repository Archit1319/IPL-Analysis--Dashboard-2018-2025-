# 📉 Gold Analysis Dashboard (2016 - 2025)

![Gold Analysis Dashboard](Image/Screenshot%20Gold.png)

## 🌟 Overview
The **Gold Analysis Dashboard** is a comprehensive data visualization project built using **Power BI**. It provides deep insights into gold price trends, market volatility, and trading patterns over the last decade (2016–2025). This dashboard is designed for investors, analysts, and enthusiasts looking to understand the historical performance of gold as a financial asset.

## 🚀 Key Features
- **Price Trend Analysis**: Visualize Open, High, Low, and Close (OHLC) prices over time.
- **Technical Indicators**: Includes Moving Averages (MA 20, MA 50, MA 200) to identify market trends and potential reversal points.
- **Volatility Tracking**: Analyze market risk through a 20-day Volatility index.
- **Seasonal Insights**: Explore price performance by Year, Quarter, Month, and even Day of the Week.
- **Volume Metrics**: Correlate price movements with trading volume to gauge market strength.
- **Interactive Drill-downs**: Filter data dynamically to focus on specific periods or performance metrics.

## 📊 Dataset Information
The analysis is based on a structured dataset (`gold_prices_10y.csv`) containing over 2,500 records. Key data points include:
- **Date**: Transaction date.
- **OHLC Prices**: Open, High, Low, and Closing prices.
- **Adj Close**: Adjusted closing price accounting for corporate actions.
- **Daily Return**: Daily percentage change in price.
- **Moving Averages**: 20, 50, and 200-day windows for trend analysis.
- **Time Features**: Enrichment with Year, Month, Quarter, and Weekday for seasonal analysis.

## 🛠️ Tech Stack
- **Data Integration**: Power Query
- **Data Modeling**: DAX (Data Analysis Expressions)
- **Visualization**: Power BI Desktop
- **Data Source**: CSV (10 Years of Gold Price History)

## 📂 Project Structure
```text
Gold Analysis Dashboard/
├── Dashboard/
│   └── gold.pbix          # Main Power BI Dashboard file
├── Data/
│   └── gold_prices_10y.csv # Raw dataset used for analysis
├── Image/
│   └── Screenshot Gold.png # Dashboard preview screenshot
└── README.md              # Project documentation
```

## ⚙️ How to Use
1. **Prerequisites**: Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
2. **Open the Project**: Navigate to the `Dashboard/` folder and open `gold.pbix`.
3. **Data Refresh (Optional)**: If the data source path needs updating, go to `Transform Data > Data Source Settings` and point to the `Data/gold_prices_10y.csv` file on your local machine.
4. **Interact**: Use the slicers and interactive elements to explore different timeframes and metrics.

---
*Created with ❤️ for data-driven insights.*
