# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim :
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm :
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program :

string = "google"

reversed_string = ""

for char in string:

    reversed_string = char + reversed_string

if string == reversed_string:

    print("Palindrome")
else:

    print("Not a Palindrome")
## Output :
<img width="201" height="35" alt="image" src="https://github.com/user-attachments/assets/dae74ceb-fc54-459a-b180-648167de87f7" />

## Result :
Thus the program is excuted and the result is obtained.
