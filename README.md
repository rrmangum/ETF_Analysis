# ETF Analysis Web Application

This project focused on building a financial database and web application (locally deployed) by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF. Analysis of a fintech ETF consisting of four stocks: GOST, GS, PYPL, and SQ. Each stock has its own table in the etf.db database. The daily returns of the ETF stocks are analyzed both individually and as a whole. The analysis is ultimately deployed to a web application by using the Voilà library.

![ETF Portfolio Cumulative Returns.png](https://github.com/rrmangum/ETF_Analysis_Web_Application/blob/main/images/Portfolio_Cumulative_Returns.png?raw=true)

---

## Locally Deployed Analysis With Voila

![voila_screenshot.png](https://github.com/rrmangum/ETF_Analysis_Web_Application/blob/main/images/voila_screenshot.png?raw=true)

---

## Technologies

This analysis uses python Python 3.9.12 and the following libraries:
* [Pandas](https://pandas.pydata.org/) - Provides the calculating functions, and data manipulation necessary to conduct this analysis.
* [SQLAlchemy](https://www.sqlalchemy.org/) - Provides a Pythonic domain language access to databases.
* [hvplot](https://hvplot.holoviz.org/user_guide/index.html) - Provides the visualizations.
* [Voilà](https://voila.readthedocs.io/en/stable/index.html) - Converts a jupyter notebook to an interactive dashboard

---

## Installation Guide

An installation is not required for this analysis if you are only wanting to review the analysis. If you wish to alter the inputted values, follow the steps below:

1. Download [Anaconda](https://www.anaconda.com/products/distribution) to your computer. In your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:

```python
jupyter lab
```
2. To install hvplot, in your terminal or gitbash enter the following command:

```python
conda install -c pyviz hvplot geoviews
```

3. To install SQLAlchemy, in your terminal or gitbash enter the following command:

```python
pip install SQLAlchemy
```

4. To install Voilà, in your terminal or gitbash enter the following command:

```python
conda install -c conda-forge voila
```

---

## Usage

This analysis is not meant as financial advice, and is purely a review of an ETF based portfolio.

---

## Contributors

Ryan Mangum - [LinkedIn](https://www.linkedin.com/in/ryanrmangum/) | rrmangum@gmail.com

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) [2022] [Ryan Mangum]

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
