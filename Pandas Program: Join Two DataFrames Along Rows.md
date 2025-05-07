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
student_data1 = {
    'Name': ['Alice', 'Bob'],
    'Age': [22, 24],
    'Grade': ['A', 'B']
}
df1 = pd.DataFrame(student_data1)
student_data2 = {
    'Name': ['Charlie', 'David'],
    'Age': [23, 21],
    'Grade': ['A', 'C']
}
df2 = pd.DataFrame(student_data2)
combined_df = pd.concat([df1, df2], axis=0, ignore_index=True)
print(combined_df)

```
## Output
![image](https://github.com/user-attachments/assets/7c69e1e2-4278-4493-8ad9-c129fb536c2b)

## Result
Thus the above program was executed successfully.
