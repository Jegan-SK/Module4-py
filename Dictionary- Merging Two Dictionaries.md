## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

    dict1={1:"one",2:"two",3:"three"}
    dict2={4:"four",5:"five",2:"Two"}
    print("Original dictionaries are :")
    print(dict1)
    print(dict2)
    dict1.update(dict2)
    print("Merged dictionary:",dict1)

## Output

<img width="1251" height="112" alt="image" src="https://github.com/user-attachments/assets/1a24dfa5-f15d-45bc-8b84-813c07a4de1b" />


## Result

Thus the python program to merge two dictionaries is written and executed successfully.
