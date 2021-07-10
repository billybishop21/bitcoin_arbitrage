# Bitcoin Arbitrage Opportunity

---

This application will entail sorting through trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. Once extracted the data from both exchanges, a three phase financial analysis will be completed to determine if any arbitrage opportunities exist for Bitcoin.

---

## Technologies

The following libraries and dependencies were used:
```python
import pandas as pd
import numpy as np
from pathlib import Path
%matplotlib inline
```

---

## Usage

### 1. Collection of Data

Bitcoin prices were collected from Bitstamp and Coinbase with the goal of locating potential arbitrage opportunities.

### 2. Preparing Data

Data clean was performed including dropping missing values, removing "$" from dataframe, convert all data to `float` and review and drop if duplicated values are found.

### 3. Analysis of Data

Data was narrowed down in order to focus analysis on three separate dates. Summary statistics were calculated on each specific date and compared using line and box plots. Preliminary pre-expense arbitrage profits were calculated. 

### 4. Calculating Arbitrage Profits

Arbitrage spreads were calculated on each of the three specific dates using coinbase bitcoin prices subtracted from bitstamp bitcoin prices. Spread returns were calculated using only positive profits for each date. Spread returns were then calculated to factor in 1% costs and taken out of profits to return profitable trades minus expenses. Data cleaning was performed after spreads, returns and expenses were calculated. 

---

## Contributors

This analysis was brought to you by Billy Bishop

---

## License

TBD

---




