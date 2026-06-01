# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = "google"

rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

## Output
<img width="415" height="160" alt="{8150C27C-CE5C-41A7-90CD-DD3CFCEDA783}" src="https://github.com/user-attachments/assets/c87ee5d7-b148-4ed0-8b45-ea24606ebd62" />

## Result
The program successfully reverses the string using slicing and checks whether it is a palindrome. Since "google" is not equal to its reverse "elgoog", the output is "Not a Palindrome".
