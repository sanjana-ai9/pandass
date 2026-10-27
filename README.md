# Day 18: Pandas Data Selection Using `loc` and `iloc`

## 📌 Project Description

This project demonstrates how to select specific rows and columns from a dataset using Pandas in Python. A student dataset containing names, ages, and marks was created for practice.

## 🎯 Objective

To understand how to select rows and columns using Pandas `loc` and `iloc`.

## 🛠️ Tools Used

* Python
* Jupyter Notebook
* Pandas

## 📚 Concepts Learned

* Creating a DataFrame using Pandas.
* Selecting a specific column using `loc`.
* Selecting a specific row using `loc`.
* Selecting rows and columns using `iloc`.
* Selecting multiple columns from a dataset.

## 💻 Code Example

```python
import pandas as pd

data = {
    "Name": ["Anu", "Ravi", "Priya", "Rahul", "Sneha"],
    "Age": [20, 21, 19, 22, 20],
    "Marks": [85, 90, 78, 88, 95]
}

df = pd.DataFrame(data)

# Select the Name column
print(df.loc[:, "Name"])

# Select a row using loc
print(df.loc[2])

# Select the first column using iloc
print(df.iloc[:, 0])

# Select a row using iloc
print(df.iloc[2])

# Select Name and Marks columns
print(df.loc[:, ["Name", "Marks"]])
```

## ✅ Outcome

Successfully practiced selecting specific rows and columns from a student dataset using Pandas.

## 📝 Conclusion

This task helped me understand `loc` and `iloc`, which are useful for selecting and analyzing data in Python.
