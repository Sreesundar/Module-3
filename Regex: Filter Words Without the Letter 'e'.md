# Regex in Python: Filter Words Without the Letter 'e'

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
```
import re


l1 = []


items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']


for i in items:
    if not re.search(r"e", i):
        l1.append(i)


print("Filtered list:", l1)
```
## Output
<img width="439" height="177" alt="image" src="https://github.com/user-attachments/assets/2430fd9c-72cd-4e07-a739-55c7595699ef" />


## Result
The program successfully filters and returns all words without the letter 'e' from the list using regular expressions.


