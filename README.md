# Financial Planning of Emergency and Retirement

This analysis uses the current and historical value of cryptocurrencies, stocks and bonds held for determining whether it can be used for emergency fund account or not.

For retirement planning, this analysis provides a probable estimate of retirement as early as after 10 years or as late as after 30year, based on stock and bonds weightage using monte carlo simulation.

---

## Technologies

It supports Python 3.7 and above and has been constructed in the jupyter lab notebook named ```financial_planning_tools.ipynb```
Additionally, the following packages/libraries are used to run the analysis:

- [pandas] - for analyzing data
- [dotenv] - for loading variables from .env files
- [alpaca SDK] - for interacting with Alpaca API for stock/bond prices
- [MCForecastTools] - for carrying out monte carlo simulations


---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install jupyterlab 
  conda install -c anaconda requests
  conda install -c jmcmurray json
  pip install python-dotenv
  pip install alpaca-trade-api

```
---

## Usage

To view the analysis, navigate to the file named ```financial_planning_tools.ipynb``` notebook in the [repository directory](https://github.com/Summi-Khanna/Challenge-5) Or you can navigate to the live version in the jupyter lab directly opening from your terminal using the clone link in terminal.

An API ke and Secret Key from [Alpaca](https://app.alpaca.markets/brokerage/new-account/overview) are both required for running this jupyter notebook locally.


## Contributors
 
Summi Khanna  
Email : sam.summo2812@gmail.com  
LinkedIn : https://www.linkedin.com/in/summi-khanna-004a60187/

---

## License

MIT License

Copyright (c) 2021 Summi Khanna

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
