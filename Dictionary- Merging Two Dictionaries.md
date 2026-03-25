## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim :
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm :
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program :

dict1 = {'a': 10, 'b': 20, 'c': 30}

dict2 = {'b': 5, 'c': 15, 'd': 40}

merged_dict = dict1.copy()

for key, value in dict2.items():

    if key in merged_dict:
        merged_dict[key] += value
    else:
        merged_dict[key] = value

print("Merged dictionary:", merged_dict)

## Output :
<img width="545" height="37" alt="image" src="https://github.com/user-attachments/assets/e35fb800-f8f8-4a22-8f39-47bdecde66e9" />

## Result :
Thus the program is excuted and the output is obatined.
