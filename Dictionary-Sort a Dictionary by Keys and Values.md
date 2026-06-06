# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

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

---

## 🧪Program
```
dictionary = {
    'c': 'orange',
    'a': 'apple',
    'b': 'banana'
}

sorted_keys = dict(sorted(dictionary.items()))

sorted_values = dict(
    sorted(dictionary.items(), key=lambda item: item[1])
)

print("Original Dictionary:", dictionary)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
```

## Sample Output

<img width="712" height="163" alt="image" src="https://github.com/user-attachments/assets/557ec1e0-8ff0-442f-9024-9b4dd9b06ddd" />


## Result

Thus, the Python program to sort a dictionary by its keys and values was executed successfully and the output was verified.

