# File Handling in Python: Count Number od words in it.

## 🎯 Aim
To write a Python program that counts the number of words in text file..

## 🧠 Algorithm

1.Define a function to create a file and write given content to it.
2.Define another function to read the file, split its content into words, and count them.
3.Define a third function to read and return the entire content of the file.
4.Each function opens the file using a with statement to ensure proper handling.
5.Return results as needed (word count or file content).

## 🧾 Program
```
def create_file(file_path,file_content):
    with open(file_path,'w')as f:
        f.write(file_content)
def count_words_in_file(file_path):
    with open (file_path,'r') as f1:
        text=f1.read()
        s=text.split()
        return len(s)
def read_file(file_path):
    with open (file_path,'r') as f2:
        return f2.read()
```

## Output
![image](https://github.com/user-attachments/assets/50a372ab-d0e2-4c28-823b-e2143dba06de)


## Result
Thus the program executed successfully.
