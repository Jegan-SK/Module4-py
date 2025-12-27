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

    data = {
        'banana': 3,
        'apple': 5,
        'orange': 2,
        'mango': 4
    }

    sorted_by_keys = dict(sorted(data.items()))
    sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

    print("Original Dictionary:")
    print(data)

    print("\nDictionary Sorted by Keys:")
    print(sorted_by_keys)

    print("\nDictionary Sorted by Values:")
    print(sorted_by_values)


## Sample Output

<img width="1239" height="188" alt="image" src="https://github.com/user-attachments/assets/871afba5-6b2f-41db-af92-2896ada391ae" />


## Result

Thus the python program to sort a dictionary by keys and values, is written and executed successfully.

