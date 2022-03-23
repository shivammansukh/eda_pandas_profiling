# Pandas Profiling
************************************************************

## Introduction
--------------------------------------------------------------

### Pandas profiling is an open source Python module with which we can quickly do an exploratory data analysis with just a few lines of code.It also generates interactive reports in web format that can be presented to any person, even if they don’t know programming.
--------------------------------------------------------------

'How to use pandas profiling'

> Using pip:
'''Install using pip package manager by running-'''
'''pip install pandas'''
'''pip install pandas-profiling''''

> Using conda:
Install using the conda package manager by running-
conda install -c conda-forge pandas
conda install -c conda-forge pandas-profiling

> Using requirements.txt:
pip install requirements.txt


## Getting Started
--------------------------------------------------------------

> Use following code to generate report:

''' import pandas_profiling as pp '''
''' df = pd.read_csv('./data/iris.csv') '''
profile = pp.ProfileReport(df)
profile.to_file("./output/pandas_profiling_output.html")'''

Here we are, it’s been that simple. We can see the report generated in the output.html file.

### For more reference visit:https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/pages/introduction.html
