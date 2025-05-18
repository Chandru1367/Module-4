
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```python
class cse:
    def mech(self):
        a=int(input())
        area=3.141592*a*a
        print("Area of circle:",round(area,2))
c=cse()
c.mech()

```
## Output

![image](https://github.com/user-attachments/assets/e320e735-1026-4d5a-b6db-c4e3ba115f20)


## Result

Thus the program executed successfully.

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```python
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

def merge(dict1, dict2):
    res = {**dict1, **dict2}
    return res

dict3 = merge(dict1, dict2)
print(dict3)

```

## Output


![image](https://github.com/user-attachments/assets/21cdc280-d148-47c0-9642-5a48f8c3f807)

## Result

Thus the program executed successfully.

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
```python
def dictionairy():
    key_value = {}
    key_value[2] = 56 
    key_value[1] = 2
    key_value[5] = 12
    key_value[4] = 24
    key_value[6] = 18 
    key_value[3] = 323

    print("Keys and Values sorted in alphabetical order by the value")
    print(sorted(key_value.items(), key=lambda kv: (kv[1], kv[0])))
dictionairy()
```

## Output

![image](https://github.com/user-attachments/assets/5579e543-5ae1-4646-9b36-b643f92ae3a0)


## Result

Thus the program executed successfully.

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

```python

list1=[5, 10, 20]
try:
    print(list1[5])
except:
    print("You're out of list range")

```
## Output

![image](https://github.com/user-attachments/assets/1eafb447-c6ac-4064-a138-c77886096a9c)


## Result

Thus, the program has been successfully executed.

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```python
file=open("story.txt","r") 
count=0 
for lines in file: 
   if lines [0] not in 'T': 
      count+=1 
print(count)
```

## Output


![image](https://github.com/user-attachments/assets/1b8a09de-5e08-49a4-af42-7780771e1274)


## Result

Thus, the program has been successfully executed.
