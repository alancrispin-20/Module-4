# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim :

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm :

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program :
 my_dict = {'b': 'banana', 'a': 'apple', 'd': 'date', 'c': 'cherry'}

sorted_keys = dict(sorted(my_dict.items()))

sorted_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("Sorted by keys:", sorted_keys)

print("Sorted by values:", sorted_values)

## Sample Output :
<img width="728" height="52" alt="image" src="https://github.com/user-attachments/assets/acfa8855-0607-4192-93d9-84277938137f" />

## Result :
Thus the program is excuted and the output is obtained.
