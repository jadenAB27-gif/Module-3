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
<img width="802" height="279" alt="image" src="https://github.com/user-attachments/assets/80365663-846e-4c7a-99f5-98b581f812c0" />

## Output
<img width="582" height="107" alt="image" src="https://github.com/user-attachments/assets/1de55746-2e84-49ad-acb8-a11ac654e280" />

## Result
<img width="582" height="107" alt="image" src="https://github.com/user-attachments/assets/c9923520-cfb5-4e31-9eb2-ec056dc35c45" />
