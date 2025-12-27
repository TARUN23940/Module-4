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
~~~
input_file_path = 'test_case_1.txt'
output_file_path = 'reversed_1.txt'
file_content = input()
create_file(input_file_path, file_content)
reverse_file_content(input_file_path, output_file_path)
print( read_file(output_file_path))
def create_file(a,b):
    with open(a,'w') as f:
        s=f.write(b[::-1])
        
def reverse_file_content(c,d):
    with open(c,'r') as r:
        q=r.read()
    with open(d,'w') as g:
        g.write(q)
def read_file(v):
    with open(v,'r')as i:
        return(i.read())
~~~
## Output
<img width="723" height="213" alt="image" src="https://github.com/user-attachments/assets/aa7e8c00-0449-413d-919d-f8fc4a3cf5d4" />

## Result
Thus, the program has been successfully executed.
