# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program

    L=[1,2,3]
    try:
        n=int(input("Enter the index:"))
        a=L[n]
        print(f"The element of index {n} is:{a}")
    except IndexError:
        print("Index out of range. Please enter correct index")
    

## Output

<img width="1254" height="64" alt="image" src="https://github.com/user-attachments/assets/3c9469d1-ae3f-4c17-9e4f-0cd4bd9efa55" />

## Result

Thus the python program to handle IndexError when trying to access a element beyond the available range of a list, is written and executed successfully.
