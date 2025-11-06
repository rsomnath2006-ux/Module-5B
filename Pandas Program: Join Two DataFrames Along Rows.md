# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd

a=eval(input())
b=eval(input())
c=pd.DataFrame(a)
d=pd.DataFrame(b)
print(f"Original DataFrames:\n{c}")
print("-" * 37)
print(f"{d}")
e=pd.concat([c,d], axis=1)
print(f"\nJoin the said two dataframes along columns:\n{e}")
```
## Output
<img width="1263" height="488" alt="image" src="https://github.com/user-attachments/assets/e75e3088-3027-4e87-8e77-540a545d97f9" />

## Result
Thus,the program is executed successfully
