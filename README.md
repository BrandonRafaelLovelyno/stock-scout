# Stock-Scout

Stock-Scout is a website scraper designed to scout stocks that meet specific technical indicator values such as **RSI, ADX, and MACD**.

## Project Overview
This scraper performs two stages of data collection:
1. **Scraping TradingView**: Retrieves stock codes based on predefined criteria.
2. **Scraping Yahoo Finance**: Iterates over the collected stock codes to fetch price history data and calculate technical indicators.

## Features
- Fetches stock codes from **TradingView**.
- Retrieves historical price data from **Yahoo Finance**.
- Computes key technical indicators (**RSI, ADX, MACD**).
- Outputs the processed data into an **Excel file**.

## Setup
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- BeautifulSoup

## Output
- The scraped and calculated stock data will be saved in an **Excel file** in the project directory.

## License
This project is for educational purposes and follows an open-source MIT License.

---

Happy stock scouting! 📈

