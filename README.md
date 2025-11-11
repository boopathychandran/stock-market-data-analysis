📊 Stock Market Data Analysis Dashboard (Power BI)
Overview
This project showcases a Power BI dashboard built to analyze NIFTY50 stock market data. It combines price history, corporate events (dividends, splits), and company fundamentals to deliver actionable insights into market trends, sector performance, and top gainers/losers.

Data Sources
NIFTY50_Master_Price.csv → Daily stock prices (Open, High, Low, Close, Volume).

NIFTY50_Master__Events.csv → Corporate actions (Dividends, Splits).

NIFTY50_Master_Info_Events.xlsx.csv → Company metadata (Name, Sector, MarketCap, PE Ratio, Business Summary).

Key Features
📈 Performance Trend: Line chart of adjusted closing prices with event markers.

🏦 Market KPIs: Total Market Cap, Sum of Market Cap, Bullish/Bearish indicator.

🏢 Top Companies: Bar chart of top 5 by market cap.

📊 Top Gainers/Losers: Pie charts showing % change leaders.

🎯 Filters: Period, Sector, and Company slicers for interactive analysis.

Challenges & Solutions
Large Price CSV → Split imports by year, optimized queries.

Date Format Issues → Standardized all dates in Power Query.

Corporate Actions → Built adjustment factors for splits, calculated trailing dividend yields.

Symbol Mismatches → Cleaned and mapped symbols for consistent joins.

Performance → Pre‑aggregated monthly snapshots, optimized DAX measures.

Insights
Reliance, HDFC Bank, Bharti Airtel, TCS, and Infosys dominate market capitalization.

Dividend yields vary widely across sectors, highlighting defensive vs. growth plays.

Sector filters reveal cyclical vs. defensive performance trends.

Future Improvements
🔄 Scheduled refresh with incremental loading.

📱 Mobile‑optimized view.

📌 Portfolio simulation for user‑selected stocks.

⚡ Anomaly detection for unusual price movements.

Tech Stack
Power BI (Data modeling, DAX, visualization)

Power Query (ETL, cleaning, transformations)

Excel/CSV (Raw data sources)

👉 This project demonstrates data preparation, modeling, and visualization skills along with the ability to solve real‑world challenges in analytics.
