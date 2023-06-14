# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i) To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Alfred A B
RegisterNumber: 212222110002
'''
def max_marks(marks):
    marks.sort()
    large=max(marks)
    return large


```

ii) To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Alfred A B
RegisterNumber: 212222110002
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Alfred A B
RegisterNumber: 212222110002
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i) To find the maximum of marks using the list method sort.

![3a 01](https://github.com/Alfredsec/FindMaximum/assets/120621608/fef751ae-853e-4da3-b6e1-2c6b70355231)

ii) To find the maximum marks using the list method max().

![3a 02](https://github.com/Alfredsec/FindMaximum/assets/120621608/3fb2091b-e9d8-48fb-ab8f-05ed1f9af2eb)

iii) To find the maximum marks without using builtin functions.

![3a 03](https://github.com/Alfredsec/FindMaximum/assets/120621608/9d566494-0e53-4f7b-91d8-644d4849910f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
