# Tesla & GameStop: Stock Price vs. Revenue Dashboard

A Python project that pulls historical stock prices with `yfinance`, scrapes quarterly revenue tables with `BeautifulSoup`, and plots both together for **Tesla (TSLA)** and **GameStop (GME)**.

This is the final project of the IBM Data Science Professional Certificate's Python project course (IBM Skills Network lab: *Extracting and Visualizing Stock Data*).

## What it does

1. **Extracts stock data** for TSLA and GME using `yfinance` (`period="max"`).
2. **Scrapes quarterly revenue** for each company from IBM-hosted HTML pages using `requests` and `BeautifulSoup`.
3. **Cleans the revenue data** by removing `$` and commas and dropping empty rows.
4. **Plots a two-panel dashboard** for each company with `matplotlib`:
   - Top panel: historical share price (US$)
   - Bottom panel: historical quarterly revenue (US$ millions)


## Tech stack

- Python 3
- [yfinance](https://pypi.org/project/yfinance/)
- pandas
- requests
- BeautifulSoup4
- matplotlib
- Jupyter Notebook

## Getting started

```bash
# 1. Clone the repo
git clone https://github.com/Ashutosh-Srivastava-git/Revenue_Data_and_Building_a_Dashboard.git
cd Revenue_Data_and_Building_a_Dashboard

# 2. Install dependencies
pip install yfinance pandas requests beautifulsoup4 matplotlib nbformat jupyter

# 3. Launch the notebook
jupyter notebook Revenue_Data_and_Building_a_Dashboard-fixed.ipynb
```

Then choose **Kernel → Restart & Run All**. An internet connection is required for the stock data and the revenue pages.
```

Then choose **Kernel → Restart & Run All**. An internet connection is required for the stock data and the revenue pages.
