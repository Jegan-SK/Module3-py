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
    import re
    items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
    for i in items:
        if re.search(r"e",i):
            pass
        else:
            print(i)

## Output

<img width="1255" height="67" alt="image" src="https://github.com/user-attachments/assets/f28d20c5-9284-494e-805b-72b413aa6b49" />


## Result

Thus the python program tofilter out and return all elements from a list that do not contajn the letter "e", using regular expressions is written and executed successfully.
