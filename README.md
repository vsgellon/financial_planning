# Financial Planning and Forecasting Tool
Analyze the value of an investment portfolio to determine the financial health of a member.
Use Monte Carlro simulation to forecast the growth of a mixed portfolio and determine if a different mix will lead to greater or lesser long-term returns.


## Technologies

This is a python command-line interface application which uses python 3.7 along with various APIs and SDKs. Specifically the Alpaca trade API was called with the Alpaca SDK. This program also utilizes .env file to call API keys 

---

## Installation Guide
Install the following dependencies:
import requests
import json
import pandas as pd
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
import os
from dotenv import load_dotenv
%matplotlib inline

---

## Usage


To use this financial planning application simply clone the repository and run the **financial_planning_tools.ipynb** with:

```python
python app.py
```

---

## Contributors

THis program was brought to you by Vic Gellon vsgellon@gmail.com

---

## License

This software is not licensed. 

