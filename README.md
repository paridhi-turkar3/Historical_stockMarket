# 📊 Multi-Stock Market Analysis (NSE & BSE)

## 📌 Problem Description
Investors and analysts often need to study and compare multiple stock performances over a long period to identify trends, correlations, and potential investment opportunities.  
Manually downloading, cleaning, and analyzing this data from different sources is **time-consuming and error-prone**.  

This project solves the problem by **automating the process of fetching, cleaning, and visualizing historical stock market data** for multiple companies from both **NSE (National Stock Exchange)** and **BSE (Bombay Stock Exchange)**.

---

## 💡 Project Idea
The idea is to build a **data-driven tool** that:  
- Fetches historical stock price data automatically using **Yahoo Finance API (`yfinance`)**.  
- Preprocesses and cleans the data for analysis.  
- Combines data of multiple companies into a single dataset.  
- Provides **visual insights** through line charts for closing price trends.  
- Saves the final dataset for future research or model training.  

---

## ⚙️ Implementation Details
1. **Data Collection**  
   - Used `yfinance` to download **5 years of historical stock data**.  
   - Selected multiple companies: Reliance, TCS, Infosys, SBI, and HDFC Bank (from both NSE & BSE).  

2. **Data Preprocessing**  
   - Extracted only the **Closing Prices** for comparison.  
   - Handled missing values using **forward-fill**.  
   - Merged all companies’ stock data into one consolidated dataset.  

3. **Data Export**  
   - Saved final dataset into `Multiple_Stocks.csv`.  
   - Enabled easy download for further use.  

4. **Visualization**  
   - Plotted line graphs of closing prices for all selected companies.  
   - Added labels, legends, and titles for better readability.  

---

## 🛠 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - `yfinance` → Fetching historical stock data  
  - `pandas` → Data cleaning & preprocessing  
  - `matplotlib` → Data visualization  
  - `google.colab` → File export & notebook execution  

---

## ✨ Features
- 📈 Fetches **real-time historical stock data** from Yahoo Finance.  
- 📊 Comparative visualization of multiple companies in one chart.  
- 📂 Automatic **CSV export** for data reuse.  
- 🔄 Handles missing values and ensures clean data.  
- ⚡ Works with both **NSE (.NS)** and **BSE (.BO)** tickers.  

---

## 🚀 Deliverables
- Jupyter Notebook: `_presention_5.ipynb`  
- Consolidated Dataset: `Multiple_Stocks.csv`  
- Stock Price Trend Visualization (Matplotlib Line Chart)  
- Documentation: README.md (this file)  

---

## 📌 Future Improvements
- Add **technical indicators** (RSI, MACD, Moving Averages).  
- Build an **interactive dashboard** with Plotly/Dash/Streamlit.  
- Automate **daily stock data updates**.  
- Extend to **international markets** (NASDAQ, NYSE, etc.).  

---

## 📝 Conclusion
This project demonstrates the power of **Python for financial data analysis** by automating data collection, preprocessing, and visualization.  
By comparing multiple companies side by side, investors and analysts can make more **informed, data-driven decisions**.  
With future enhancements such as dashboards and real-time updates, this tool can evolve into a **comprehensive stock market analytics platform**.  

---

## 📚 References
- [Yahoo Finance API (`yfinance`)](https://pypi.org/project/yfinance/)  
- [NSE India](https://www.nseindia.com/)  
- [BSE India](https://www.bseindia.com/)  
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)  
- [Pandas Documentation](https://pandas.pydata.org/)  

