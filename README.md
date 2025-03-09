# AI-Powered Investment Research Assistant

## Overview
This project fetches **real-time** stock data using Finnhub and **historical** data from Yahoo Finance. The data is stored in **MySQL** for long-term use. Future updates will include **sentiment analysis** and **stock predictions**.

## Tech Stack
- **Python 3.12.9**
- **APIs:** Finnhub, Yahoo Finance
- **Database:** MySQL
- **Libraries:** `mysql-connector-python`, `finnhub`, `yfinance`, `pandas`, `numpy`

## Setup
1. **Install dependencies:**  
   ```bash
   pip install mysql-connector-python finnhub-python yfinance pandas numpy
   ```
2. **Set up MySQL:**  
   - Create a database: `CREATE DATABASE market_data;`
   - Run the SQL script to create tables.
3. **Run scripts:**  
   - `python real_time_data.py` (Fetch real-time data)
   - `python historical_data.py` (Fetch historical data

