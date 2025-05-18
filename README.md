# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))

```
## Output

![438584061-73e17fd1-ed4b-4ed2-b342-ff081715c4bf](https://github.com/user-attachments/assets/66305d32-3488-42d3-a8ba-0f37998fc3e6)

## Result
Thus the program executed successfully.

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
print("Words without 'e':", l1)

```
## Output

![438590374-fbe52d43-eb10-4615-bd06-3b1dde3da7d2](https://github.com/user-attachments/assets/a80859da-2d91-4ad1-bcc8-62df36ec9b89)



## Result
Thus the program executed successfully.
