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
import numpy
a=numpy.array(eval(input()))
print(f"Given array\n {a}")
b=numpy.sort(a,axis=0)
print(f"\n{b}")
```
## Output
<img width="380" height="267" alt="Screenshot 2025-11-06 134254" src="https://github.com/user-attachments/assets/dc7b9d75-9456-4a21-9515-5c5097698e53" />

## Result
Thus,the program is executed successfully
