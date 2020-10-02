# Stock-Analysis
A measure to predict the value of shares of a particular company in coming days for better investrment.   
# Quandl
# Sklearn
# Numpy
# Pandas
Quandl is a premier source for financial, economic, and alternative datasets, serving investment professionals.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install quandl.

```bash
pip install quandl numpy pandas sklearn
```
## About Dataset
This data feed offers stock prices, dividends and splits for 3000 US publicly-traded companies.

Note: As of April 11, 2018 this data feed is no longer actively supported by the Quandl community.
This project is for learning purpose so we do not recommend using it for investment or analysis.


## Usage

```python
import quandl

import numpy as np
from sklearn.linear_model import LinearRegression
from sklearn.svm import SVR
from sklearn.model_selection import train_test_split
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
