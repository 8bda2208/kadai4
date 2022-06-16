import pandas as pd

df = pd.read_csv('FEH_00200521_220610143730.csv')
print(df)

describe = df.describe()
print(describe)
describe.to_csv('FEH_00200521_220610143730_基本統計量.csv')
