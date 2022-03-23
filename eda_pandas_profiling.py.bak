import pandas as pd
import pandas_profiling as pp

df = pd.read_csv('./data/iris.csv')
profile = pp.ProfileReport(df)
profile.to_file("./output/pandas_profiling_output.html")