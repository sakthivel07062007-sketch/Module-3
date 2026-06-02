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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = []
for i in items:
    if not re.search('e', i):
        result.append(i)
print(result)
```
## Output

<img width="435" height="159" alt="568378579-a987cf10-57a1-4836-95fe-eb2e8fc6fe9e" src="https://github.com/user-attachments/assets/3cd47bd8-f057-4769-9646-961467f0cf22" />

## Result
Thus, the program has been executed successfully.
