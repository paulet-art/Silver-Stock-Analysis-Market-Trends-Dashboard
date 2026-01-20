# 💎 Silver Stock Analysis & Market Trends Dashboard

## Overview
This project explores historical silver stock prices using **daily trading data**, providing insights into price trends, market volatility, and trading activity. The analysis is implemented in **Power BI**, combining interactive visuals and KPIs to deliver a **user-friendly dashboard** for investors, analysts, and enthusiasts.

The dataset includes key stock metrics from January 2021 to March 2022, such as Open, High, Low, Close, Adjusted Close, Volume, moving averages, and calculated returns.

---

## Key Features

- **Price Trends & Moving Averages**
  - Line charts for **Close** and **Adjusted Close** prices.
  - 50-day and 200-day moving averages to identify **short- and long-term trends**.

- **Daily Returns & Volatility**
  - Daily return calculation shows **percentage change day-to-day**.
  - Rolling 30-day volatility highlights **market risk and fluctuations**.

- **Trading Activity**
  - Volume charts reveal **market participation** and periods of high activity.

- **Time-Based Analysis**
  - Yearly and monthly breakdowns to identify **seasonal patterns** in silver trading.

- **KPI Cards**
  - Quick metrics: latest Close price, average daily return, 30-day volatility, and total traded volume.

---

## Dataset Columns

| Column | Description |
|--------|-------------|
| Date | Trading date |
| Open | Opening price of silver for the day |
| High | Highest price during the day |
| Low | Lowest price during the day |
| Close | Closing price for the day |
| Adj Close | Adjusted closing price (accounts for splits/dividends) |
| Volume | Total traded volume |
| MA_50 | 50-day moving average of Close |
| MA_200 | 200-day moving average of Close |
| Daily_Return | Daily percentage change in Close price |
| Year | Year extracted from Date |
| Month | Month extracted from Date |
| Volatility_30d | 30-day rolling volatility of Daily_Return |

---

## Purpose & Insights

This dashboard demonstrates:

- **Trend identification** using moving averages.  
- **Risk analysis** via daily returns and volatility metrics.  
- **Market behavior understanding** through trading volumes and seasonal trends.  
---

## Technologies Used

- **Power BI Desktop**: Dashboard creation, DAX calculations, interactivity  
- **Excel / CSV**: Dataset preparation and cleaning  
- **DAX Functions**: `AVERAGE`, `LASTNONBLANK`, `AVERAGEX`, etc. for KPIs and calculated columns  

