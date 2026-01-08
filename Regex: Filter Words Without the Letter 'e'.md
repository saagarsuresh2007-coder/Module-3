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
<img width="803" height="320" alt="image" src="https://github.com/user-attachments/assets/06106069-c131-4399-be09-13cb509cb5ed" />
## Output
<img width="827" height="152" alt="image" src="https://github.com/user-attachments/assets/1121c950-aa75-408a-89c2-cc94bec193f4" />

## Result
<img width="827" height="152" alt="image" src="https://github.com/user-attachments/assets/0833b16a-5605-46e0-8405-43b7d8a1e9e7" />
