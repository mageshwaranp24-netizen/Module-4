# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30]

try:
    result = list1[5]  # Out of range index
    print(result)
except IndexError:
    print("You're out of list range")

```

## Output
<img width="622" height="159" alt="image" src="https://github.com/user-attachments/assets/bb308cfb-8839-47b9-837d-ce6bbd79b88a" />

## Result
Thus the Python program that handles an IndexError when trying to access an element beyond the available range of a list was executed successfully.
