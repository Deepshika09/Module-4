# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values


## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**



## 🧪Program
```

d = {"apple": 50, "banana": 20, "cherry": 40, "date": 10}

sorted_by_keys = dict(sorted(d.items()))
sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original Dictionary:", d)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)


```
## Sample Output
<img width="797" height="229" alt="image" src="https://github.com/user-attachments/assets/4e65cfd9-18af-4e16-83d4-cb970975bab5" />

## Result
Therefore the program was executes successfully.
