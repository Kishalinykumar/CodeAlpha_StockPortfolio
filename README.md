# CodeAlpha_StockPortfolio
Stock-Portfolio Tracker developed using python for python programming internship at CodeAlpha (Task2)


# Stock Portfolio Tracker

## Overview
This is a web-based stock portfolio tracker built using Flask and Yahoo Finance API (yfinance). It allows users to add, remove, and track stocks in their portfolio. The application fetches real-time stock prices and calculates the total portfolio value.

## Features
- Add stocks with a specified quantity.
- Remove stocks from the portfolio.
- Fetch real-time stock prices using Yahoo Finance.
- Display the total portfolio value.
- Responsive and visually appealing interface with CSS styling.

## Technologies Used
- **Python** (Flask for web framework)
- **Yahoo Finance API** (yfinance for fetching stock data)
- **HTML, CSS** (Frontend for displaying stock data)

## Prerequisites
- Python 3.x
- Required Python Libraries:
  ```bash
  pip install flask yfinance
  ```

## Installation & Running the Application
1. Clone the repository or copy the code files.
2. Navigate to the project directory.
3. Install dependencies using:
   ```bash
   pip install flask yfinance
   ```
4. Run the Flask application:
   ```bash
   python main.py
   ```
5. Open a web browser and go to `http://127.0.0.1:5000/`

## Folder Structure
```
/stock-portfolio-tracker
│── main.py  # Flask backend
│── templates/
│   └── index.html  # HTML frontend
│── static/
│   └── style.css  # CSS for styling
```

## Usage
1. Open the web application in a browser.
2. Add stocks by entering the stock symbol and quantity.
3. View real-time stock prices and portfolio value.
4. Remove stocks as needed.

## Example Interaction
```
User adds 5 shares of AAPL
User adds 3 shares of TSLA
Application fetches real-time prices
Total portfolio value is displayed
```

## License
This project is open-source and free to use.

## Author
Created by [Kishaliny K]

