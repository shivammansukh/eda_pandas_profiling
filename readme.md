### Features

# Pandas Profiling

## Introduction
Pandas profiling is an open source Python module with which we can quickly do an exploratory data analysis with just a few lines of code. It also generates interactive reports in web format that can be presented to any person, even if they do not know programming.

- How to install pandas profiling and other required libraries:

> Using pip:
pip install pandas
pip install pandas-profiling

> Using conda:
conda install -c conda-forge pandas
conda install -c conda-forge pandas-profiling

> Using requirement.txt file:
pip install -m requirements.txt

## Getting Started
- Use following code to generate a report:
```
import pandas_profiling as pp
df = pd.read_csv('./data/iris.csv') 
profile = pp.ProfileReport(df)
profile.to_file("./output/pandas_profiling_output.html")
```

##### Here we are, it is been that simple. We can see the report generated in the output.html file.

## Reference
https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/pages/introduction.html