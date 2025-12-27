# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program

    def countlines(file):
        c=0
        f=open(file,"r")
        for i in f.readlines():
            if i[0]!="T":
                c+=1
        print(c)
    
    countlines("story.txt")

## Output

<img width="1262" height="44" alt="image" src="https://github.com/user-attachments/assets/61d4095d-3a63-479e-8cc4-4d2e88c12f0d" />

## Result

Thus the python program to count the number of lines in atext file "story.txt" that do not start with the alphabet "T"
, is written and executed successfully
