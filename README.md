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

## i)	To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: shabreena vincent
RegisterNumber: 212222230141
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

## ii)	 To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: shabreena vincent
RegisterNumber: 212222230141
'''
def max_marks(marks):
     marks.sort()
     return marks[-1]


```

## iii) To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: shabreena vincent
RegisterNumber: 212222230141
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```
##  Output:

## i)	To find the maximum of marks using the list method sort.

![max 1](https://github.com/shabreenavincent/FindMaximum/assets/119475721/541e3192-2d7d-42fd-8f0a-b95965997a6f)


## ii)	 To find the maximum marks using the list method max().





![max2](https://github.com/shabreenavincent/FindMaximum/assets/119475721/8d1ad959-883a-4427-b0f2-201f72ece6df)



## iii) To find the maximum marks without using builtin functions.




![max3](https://github.com/shabreenavincent/FindMaximum/assets/119475721/c943ec53-255a-4b11-b524-4ce328d7868b)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
