# Ex3(a) List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
Developed By: Subash M
Reg No: 212224220109
```
items=[153,147,124,102]
print(sum(items))
```

## Output

![image](https://github.com/user-attachments/assets/9a4aad2b-da78-4470-ac70-73f27d29afd0)

## Result
Thus, the python program was executed successfully.

# Ex:3(b) Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
Developed By: Subash M
Reg no: 212224220109
```

import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```
## Output

![image](https://github.com/user-attachments/assets/61c34bf0-958f-4b48-9789-50f6fd79e0fb)


## Result

Thus, the python program was executed successfully.

# Ex:3(c) 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
Developed By: Subash M
Reg NO: 212224220109

```
def remove(str): 
  l=len(str) 
  a="" 
  n=int(input()) 
  for i in range(0,l): 
    if i==n: 
      a=a+"" 
    else: 
      a=a+str[i] 
print(a)
```

## Output


![image](https://github.com/user-attachments/assets/4c874672-75aa-4958-9b94-2862ded7a87d)


## Result

Thus the program has been successfully executed

# Ex:3(d) Strings-Palindrome Check in Python (Without Built-in Functions)

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
Developed By: Subash M
Reg NO: 212224220109

```
string="google" 
if string==string[::-1]: 
   print ("The entered string is palindrome") else: 
   print ("The entered string is not palindrome")
```

## Output

![image](https://github.com/user-attachments/assets/676f5a72-43cb-449b-8ab2-fc3b3bab848f)

## Result

Thus, the program has been successfully executed.

# Ex:3(e) Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
Developed By: Subash M
Reg No: 212224220109

```
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
```

## Output

![image](https://github.com/user-attachments/assets/8e99426d-d24d-4692-a30f-780455a80e2e)

## Result

Thus the program executed successfully.

