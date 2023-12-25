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
Program to mark the maximum of marks using the list method sort
Developed by: PRAVIN KUMAR A.
RegisterNumber: 23007430
'''
def max_marks(marks):
    a=marks.sort()
    b=marks[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: PRAVIN KUMAR
RegisterNumber: 23007430
'''
def max_marks(marks):
    large = max(marks)
    return large
   


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: PRAVIN KUMAR A.
RegisterNumber: 23007430
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max :
            max=i
    return max
    


```
## Output:
i)	# To find the maximum of marks using the list method sort.
![3a1](https://github.com/RAVENPRAVIN/FindMaximum/assets/146820534/44279cec-f153-4e14-8d86-153af66dfe93)

ii)	# To find the maximum marks using the list method max().
![3a2](https://github.com/RAVENPRAVIN/FindMaximum/assets/146820534/39f16aeb-ec36-4618-8ab6-873409eed5f3)

iii) # To find the maximum marks without using builtin functions.
![3a3](https://github.com/RAVENPRAVIN/FindMaximum/assets/146820534/5ae1d113-550c-4712-a5b0-24498111baa0)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
