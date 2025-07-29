# 📈 IEX Stock Analysis & Prediction

This project performs **Exploratory Data Analysis (EDA)**, **data visualization**, and **predictive modeling** using real-time and historical stock data from [The Investors Exchange (IEX)](https://iextrading.com/apps/stocks/). It aims to understand stock behavior, evaluate investment risks, and forecast future price movements using statistical methods like the **Monte Carlo Simulation**.

> 📘 **[View Full Notebook](https://nbviewer.jupyter.org/github/anwarcsebd/stock-market-analysis/blob/master/stock-market-analysis.ipynb)**

---

## 🚀 Overview

Using **Python**, this project gathers stock market data via `pandas-datareader` from the IEX Developer API. Key components include:

- 📊 Exploratory Data Analysis (EDA)
- 📉 Visualization of price trends and indicators
- 📈 Risk and return analysis
- 🔮 Monte Carlo simulations for stock price prediction

---

## 🧰 Tools & Libraries

- **Python 3.6**
- **Jupyter Notebook 5.6.0**
- Python Libraries:
  - `numpy 1.14.2`
  - `pandas 0.23.4`
  - `pandas-datareader 0.6.0`
  - `matplotlib 2.10.0`
  - `seaborn 0.8.0`

---

## 📦 Data Source

All stock data is retrieved from the **IEX Developer API** using `pandas-datareader`.

- Real-time stock quotes
- Historical price data
- Fundamentals and market statistics

🔗 [IEX API Documentation](https://iextrading.com/developer/)

---

## 🔍 Key Features

- Fetch historical stock price data
- Compute moving averages and returns
- Visualize trends and correlations
- Analyze portfolio risk using standard deviation
- Predict stock prices using Monte Carlo Simulation

---

## 📁 Project Structure

```bash
iex-stock-analysis/
│
├── stock-market-analysis.ipynb     # Main analysis notebook
├── README.md                       # Project documentation
