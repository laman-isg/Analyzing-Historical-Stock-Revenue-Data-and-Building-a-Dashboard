# Stock & Revenue Data Analysis and Dashboard

This project extracts and analyzes historical stock prices and quarterly revenue data for Tesla and GameStop. It uses **yfinance** to get stock data and **BeautifulSoup** to scrape revenue data from webpages. The data is cleaned and visualized with **Plotly** to build interactive dashboards showing price and revenue trends up to mid-2021.

---

## Features

- Fetches max-period stock data for TSLA and GME using yfinance  
- Scrapes quarterly revenue data from HTML tables  
- Cleans and preprocesses data (removes `$`, commas, and empty entries)  
- Visualizes historical stock prices and revenues in combined interactive plots  

---

## Usage

1. Install required packages:  
   `pip install yfinance requests beautifulsoup4 pandas plotly`

2. Run scripts/notebook cells in order from data extraction to visualization.

3. Use `make_graph(stock_data, revenue_data, 'CompanyName')` to plot graphs.
