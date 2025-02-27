# DataFrames and Series in Pandas

## 1. Pandas Series
A **Series** in Pandas is a **one-dimensional** labeled array that can hold any data type (integers, floats, strings, etc.).

### Creating a Series
```python
import pandas as pd

# Creating a Series from a list
data = [10, 20, 30, 40]
series = pd.Series(data)

print(series)
