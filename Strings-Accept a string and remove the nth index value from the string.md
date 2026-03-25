# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim :
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm :
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program :

string = input("Enter a string: ")
index = int(input("Enter the index to remove: "))

new_string = string[:index] + string[index+1:]

print("Updated string:", new_string)

## Output :
<img width="236" height="55" alt="image" src="https://github.com/user-attachments/assets/bbcb10da-1ef8-43cf-8934-5d8de43ec708" />

## Result :
Thus the program is excuted and the output is obtained.
