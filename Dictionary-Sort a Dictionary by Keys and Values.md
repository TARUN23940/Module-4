# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

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

## 🧪Program
~~~
a=eval(input())
print('Keys and Values sorted in alphabetical order by the key')
for b,c in sorted(a.items()):
    print(f"({b}, {c})", end=' ')
~~~
## Sample Output
<img width="864" height="176" alt="image" src="https://github.com/user-attachments/assets/8cbede1c-ce1f-41b2-929b-91bfc2483a12" />

## Result
Thus, the program has been successfully executed.
