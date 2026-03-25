# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim :
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm :
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program :
my_list = [10, 20, 30, 40]

try:

    index = int(input("Enter index: "))
    print("Element:", my_list[index])
except IndexError:

    print("Error: Index out of range!")

## Output :
<img width="293" height="53" alt="image" src="https://github.com/user-attachments/assets/0e27c2ec-84fd-491a-81cd-e41386ff6fc8" />

## Result :
Thus the program is excuted and the output is obtained.
