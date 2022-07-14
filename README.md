# Portfolio Analysis Application

This application analyzes the returns of different funds, tickers, indexes from a CSV file. It analyzes on the base of Performance, Volatility, Risk, Risk-Return profile, and for diversification

---

## Technologies

Using Python 3.7

* [pandas](https://github.com/google/pandas) - For data analysis

* [numpy](https://github.com/numpy/numpy) - For mathematical functions

---

## Installation Guide

```python
  pip install pandas
  pip install numpy
```

---

## Usage

To use the Portfolio Analysis Application simply link the file path to the source data in the function on line 3, input box 2.
It analyzes performance thru visualization of the daily return data.
It analyzes volatility thru visualization of the standard deviation.
It analyzes risk thru standard deviation and beta.
It analyzes risk-return using the Sharpe ratio.
Finally, it analyzes the diversification thru testing variance, beta, and covariance.

Note, for this application to be most useful include S&P 500 index data in a column titled 'S&P 500'.


---

## Contributors

Sole Contributor - Josh Thompkins

---

## License

Everyone is free to view and work with this project, you may not alter text unless given explicit permission.
