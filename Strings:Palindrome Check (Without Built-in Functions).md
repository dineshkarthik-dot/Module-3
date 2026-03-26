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

def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
           
string =input()
palindrome(string)

## Output
<img width="948" height="157" alt="568202337-59a27709-a9cd-4d0d-ab75-9ad68be8a0ca" src="https://github.com/user-attachments/assets/65384634-b92f-40fe-a89e-0bb6e2e54c9a" />

## Result
Thus the program executed successfully.

