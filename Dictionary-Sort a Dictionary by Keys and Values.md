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
```
a=eval(input())
s=sorted(a)
s2=s
l=[]
l2=[]
res=[]
print("Keys and Values sorted in alphabetical order by the key")
for i in s2:
    l.append(i)
    l2.append(a[i])
lenn=len(s2)
for i in range(lenn):
    temp=(l[i],l2[i])
    res.append(temp)
for i in res:
    print(i,end=" ")
```

## Output
![image](https://github.com/user-attachments/assets/121ab2ac-a1ee-499d-8612-4a12c7c9a811)


## Result
Thus the program executed successfully.

