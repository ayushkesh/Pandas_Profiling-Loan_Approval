# Pandas_Profiling-Loan_Approval
# Pandas Profiling

![Pandas Profiling Logo Header](https://pandas-profiling.github.io/pandas-profiling/docs/assets/logo_header.png)

[![Build Status](https://travis-ci.com/pandas-profiling/pandas-profiling.svg?branch=master)](https://travis-ci.com/pandas-profiling/pandas-profiling)
[![Code Coverage](https://codecov.io/gh/pandas-profiling/pandas-profiling/branch/master/graph/badge.svg?token=gMptB4YUnF)](https://codecov.io/gh/pandas-profiling/pandas-profiling)
[![Release Version](https://img.shields.io/github/release/pandas-profiling/pandas-profiling.svg)](https://github.com/pandas-profiling/pandas-profiling/releases)
[![Python Version](https://img.shields.io/pypi/pyversions/pandas-profiling)](https://pypi.org/project/pandas-profiling/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

Generates profile reports from a pandas `DataFrame`. 
The pandas `df.describe()` function is great but a little basic for serious exploratory data analysis. 
`pandas_profiling` extends the pandas DataFrame with `df.profile_report()` for quick data analysis.

For each column the following statistics - if relevant for the column type - are presented in an interactive HTML report:

* **Type inference**: detect the [types](#types) of columns in a dataframe.
* **Essentials**: type, unique values, missing values
* **Quantile statistics** like minimum value, Q1, median, Q3, maximum, range, interquartile range
* **Descriptive statistics** like mean, mode, standard deviation, sum, median absolute deviation, coefficient of variation, kurtosis, skewness
