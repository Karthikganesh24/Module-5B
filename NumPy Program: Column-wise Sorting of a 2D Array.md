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
array = np.array([[12, 5, 34],
                  [2, 45, 8],
                  [21, 9, 13]])
print("Original Array:\n", array)
sorted_array = np.sort(array, axis=0)
print("Column-wise Sorted Array:\n", sorted_array)

```
## Output
![image](https://github.com/user-attachments/assets/89de8511-5f8f-4d1c-bde2-e6f8b6b261a0)

## Result
Thus the above program was executed successfully.
