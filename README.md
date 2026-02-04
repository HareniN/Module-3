# 1. List Operations in Python: Sum of List Items

## 🎯 Aim:

To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm:

1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program:

```
items=[153,147,124,102]
print(sum(items))
```

## Output:

<img width="422" height="198" alt="Screenshot 2026-02-04 114044" src="https://github.com/user-attachments/assets/ae1c7047-7710-4a3a-9ee0-bc5d5c16ff1f" />


## Result:
Thus, the program was executed successfully.



# 2. Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim:

To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm:

1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program:

```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```

## Output:

<img width="647" height="195" alt="Screenshot 2026-02-04 114135" src="https://github.com/user-attachments/assets/a9df158c-8387-437c-a3d7-ba6e75bf2ff7" />


## Result:
Thus, the program was executed successfully.




# 3. Strings-Remove Nth Index Character from a String

## 🎯 Aim:

To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm:

1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program:

```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```

## Output:

<img width="898" height="240" alt="Screenshot 2026-02-04 114229" src="https://github.com/user-attachments/assets/fc101362-6f58-48a6-832c-c23e9451974c" />


## Result:
Thus, the program was executed successfully.




# 4. Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim:

To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm:

1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program:

```
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output:

<img width="1019" height="160" alt="Screenshot 2026-02-04 114328" src="https://github.com/user-attachments/assets/078a9f06-f1e6-4c88-b777-088122a2ff04" />


## Result:
Thus, the program was executed successfully.




# 5. Tuple in Python: Check Element Existence

## 🎯 Aim:

To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm:

1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program:

```
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
```

## Output:

<img width="1004" height="296" alt="Screenshot 2026-02-04 114415" src="https://github.com/user-attachments/assets/eea193bd-ea1c-4b2f-badf-6814e03ce8cb" />


## Result
Thus, the program was executed successfully.
