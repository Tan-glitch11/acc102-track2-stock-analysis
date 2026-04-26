ACC102 Track2: Monthly Stock Analysis

## 1. Problem & User
Analyze monthly stock price and return for finance students and investors.

## 2. Data Source
- Database: WRDS CRSP
- Tables: crsp.msf, crsp.msfhdr
- Access date: 26 April 2026
- Key variables: ticker, date, price, return

## 3. Python Methods
- WRDS connection + db.raw_sql()
- Parameterised SQL with f-string
- LEFT JOIN (Week 6 lecture)
- Pandas: clean, rename, sort, date process
- Matplotlib visualization

## 4. Key Findings
- AAPL price shows upward trend from 2020.
- Monthly return has stable volatility.
- Data quality is good with few missing values.

## 5. How to Run
1. Connect to WRDS with your account.
2. Run all cells in `stock_analysis.ipynb`.
3. Install required packages: `pip install pandas matplotlib wrds`.

## 6. Links
GitHub Repo:https://github.com/Tan-glitch11/acc102-track2-stock-analysis/edit/main/README.md
Demo Video: [Your Mediasite Video Link Here]

## 7. Limitations & Improvements
- Limitations: Only one stock is analyzed; sample period is limited.
- Improvements: Extend to multiple tickers; add risk metrics like standard deviation.
