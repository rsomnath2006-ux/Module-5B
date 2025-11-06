# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
a=eval(input())
b=np.array(a)
print(b)
c=np.sort(b, axis=None)
print(f"\n{c}")
```
## Output
<img width="945" height="384" alt="Screenshot 2025-11-06 134617" src="https://github.com/user-attachments/assets/438674bf-8536-429e-bbf3-b4b4f27fca53" />

## Result
Thus,the program is executed successfully
