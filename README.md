# Crypto Analysis Excel Dashboard

## 📌 Project Overview
This project focuses on analyzing cryptocurrency market data using Excel dashboards.
It provides interactive insights for investors to understand price trends, liquidity,
market capitalization, and investment opportunities.

The project is built on the same dataset used during training and extended with
additional internship tasks.

---

## 📊 Dataset
**Source:** CoinMarketCap (scraped using Python)

**Data Fields:**
- Coin Name
- Symbol
- Current Price
- Market Capitalization
- Volume (24 Hours)
- Circulating Supply
- Price Change (1 Hour, 24 Hours, 7 Days)
- Price Range Category

The dataset is stored in the `Data` folder.

---

## 🛠 Tools & Technologies Used
- Python (Google Colab) – Data Scraping
- Excel – Pivot Tables, Charts, VBA, Dashboards
- GitHub – Project Hosting & Documentation

---

## 🔄 Data Processing & Transformation
The following steps were applied to prepare the dataset:

- Web scraping from CoinMarketCap using Python
- Data cleaning (removal of duplicates and missing values)
- Price range categorization
- Calculation of average downfall percentages
- Creation of helper columns for analysis
- Preparation of pivot tables for dashboards

---

## 📈 Key Performance Indicators (KPIs)

The project includes the following KPIs:

- Best Coin Name (Lowest Average Downfall)
- Coin Symbol
- Current Price
- Average Downfall Percentage (1h, 24h, 7d)
- Total Number of Coins
- Total Market Capitalization
- Highest Price Coin
- Total Circulating Supply

These KPIs update dynamically based on slicer selections.

---

## 📊 Dashboards

### Dashboard 1: Market Overview
- Market Capitalization Analysis
- Volume Comparison
- Price vs Supply
- Coin Comparison
- Interactive Filters

### Dashboard 2: Investor Analysis
- Price Range Analysis
- Downfall-Based Investment Selection
- Liquidity Distribution
- Time-Based Security (VBA)
- Top Performers Identification

All dashboards are interactive and connected to slicers.

---

## 📂 Project Structure

