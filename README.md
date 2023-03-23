# Pandas1
1. installing Pandas
```
pip install pandas
```
2. using pandas
```
import pandas as pd
```
3. Pandas Data Frame example

```
df2 = pd.DataFrame([
  [1, 'San Diego', 100],
  [2, 'Los Angeles', 120],
  [3, 'San Francisco', 90],
  [4, 'Sacramento', 115]
],
 columns = [
    'Store ID', 'Location', 'Number of Employees'
  ])

print(df2)
```
4. Clone this repository 

```
git clone https://github.com/goosecrash/Pandas1
```
5. Reading from example.csv

```
import pandas as pd

df = pd.read_csv('sample.csv')
print(df)
```
this prints the csv
6. 
