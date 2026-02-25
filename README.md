<<<<<<< HEAD
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
=======
# IPL Analysis Dashboard 🏏

A comprehensive **Power BI Dashboard** that provides deep insights into the Indian Premier League (IPL) performance across multiple seasons. This project analyzes player statistics, team performances, and match outcomes to deliver a visual storytelling experience.

![IPL Analysis Preview](Image/IPL%20Analysis_page.jpg)

## 📊 Overview
The IPL Analysis Dashboard is designed to help cricket enthusiasts and analysts explore the rich history of the IPL. From tracking individual player milestones to understanding team dynamics and match trends, this dashboard covers it all using data-driven visualizations.

## 🚀 Key Features
- **Match Analysis**: Insights into match results, toss decisions, and winning trends.
- **Player Performance**: Detailed statistics for batsmen and bowlers, including strike rates, economy, and milestones.
- **Team Statistics**: Comparison of team performances, win percentages, and seasonal progress.
- **Ball-by-Ball Breakdown**: Granular analysis of every delivery to identify patterns and crucial moments.
- **Interactive Filters**: Filter data by Season, Team, Player, and Venue for customized insights.

## 🛠️ Tech Stack
- **Tool**: Microsoft Power BI Desktop
- **Data Source**: CSV files (Match data, Ball-by-ball data, Player info, Team info)
- **Data Transformation**: Power Query (M Language)
- **Calculations**: DAX (Data Analysis Expressions)

## 📂 Project Structure
```text
IPL Analysis Dashboard/
├── Dashboard/
│   └── IPL Analysis.pbix       # The main Power BI project file
├── Data/
│   ├── ball_by_ball_data.csv   # Delivery-level information
│   ├── ipl_matches_data.csv    # Match-level summaries
│   ├── players-data-updated.csv# Player profiles and roles
│   └── teams_data.csv          # Team metadata
├── Image/
│   └── IPL Analysis_page.jpg   # Dashboard screenshot
└── README.md                   # Project documentation
```

## 📈 Dataset Information
The dashboard is fueled by four primary datasets:
1. **Ball-by-Ball Data**: Detailed info for every delivery bowled in IPL history.
2. **Match Data**: Summary of matches including winners, venues, and toss details.
3. **Player Data**: Information about players, their roles, and countries.
4. **Team Data**: Mapping of team names and abbreviations.

## ⚙️ How to View the Dashboard
1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone this repository or download the ZIP file.
3. Navigate to the `Dashboard/` folder.
4. Open `IPL Analysis.pbix`.
5. Ensure the data sources are linked correctly if prompted (point them to the `Data/` folder).

## 💡 Insights Gained
- Identification of the most consistent teams across seasons.
- Impact of the toss on match outcomes (Batting vs. Bowling first).
- Performance of orange and purple cap contenders.
- Venue-specific scoring patterns.

---
*Created with ❤️ for Cricket Fans!*
>>>>>>> 2bdb73543021532b935edbcd1189a3952407a85a
