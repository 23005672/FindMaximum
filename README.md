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

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: RIYA P L
RegisterNumber: 23005672
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: RIYA P L
RegisterNumber: 23005672
'''
def max_marks(marks):
    large=max(marks)
    return large 

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: RIYA P L
RegisterNumber: 23005672
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```

## Output:
![max1](https://github.com/23005672/FindMaximum/assets/138971519/ea0489eb-8132-4dd1-a69a-d30d3a9fff8c)
![max2](https://github.com/23005672/FindMaximum/assets/138971519/c323cb80-6eb1-45d3-992e-bcec643ce187)
![max3](https://github.com/23005672/FindMaximum/assets/138971519/95358ad5-57f9-4f89-a720-8213d64b92c6)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
