# CodeAlpha_StockPortfolioTracker

A simple stock portfolio tracker built in Python as part of my CodeAlpha Python Programming Internship (Task 2).

## About the Project
The user enters stock symbols and quantities. Prices come from a hardcoded dictionary. The program calculates the value of each holding and the total investment, and can save the result to a `.txt` or `.csv` file.

## Features
- Hardcoded price dictionary for 5 stocks (AAPL, TSLA, GOOGL, MSFT, AMZN)
- Input validation for stock symbols and quantities
- Entering the same stock again adds to its quantity
- Clean table showing quantity, price, value and total investment
- Optional saving of the result as `.txt` or `.csv`

## Concepts Used
- Dictionaries
- `while` loops
- Functions
- Input/output and string formatting
- Basic arithmetic
- File handling (`open`, `csv` module)

## How to Run
1. Make sure Python 3 is installed.
2. Download or clone this repository.
3. Run:

```
python stock_tracker.py
```

## Sample Output
```
=== STOCK PORTFOLIO TRACKER ===

Available stocks:
  AAPL   $180
  TSLA   $250
  GOOGL  $140
  MSFT   $320
  AMZN   $130

Enter a stock symbol and quantity. Type 'done' when finished.

Stock symbol (or 'done'): aapl
Quantity of AAPL: 4
Added 4 x AAPL.

Stock symbol (or 'done'): msft
Quantity of MSFT: 2
Added 2 x MSFT.

Stock symbol (or 'done'): done

============================================
Stock      Qty     Price         Value
--------------------------------------------
AAPL         4      $180          $720
MSFT         2      $320          $640
--------------------------------------------
Total investment:                     $1,360
============================================

Save this result to a file? (y/n): y
Save as txt or csv? txt
Saved to portfolio.txt
```

## Author
Harshada Shingade
Python Programming Intern at CodeAlpha
