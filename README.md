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
Developed by:Renuga.S
RegisterNumber:212222230118

def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:Renuga.S 
RegisterNumber:212222230118 

def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

Program to the maximum marks without using builtin functions.
Developed by:Renuga.S 
RegisterNumber:212222230118 

def max_marks(list1):
    maxvalue=list1[0]
    for i in range(1,len(list1)):
        if list1[i]>maxvalue:
            maxvalue=list1[i]
    return maxvalue


``` 

## Output:


![METHOD SORT(MAX)](https://user-images.githubusercontent.com/119292258/235332355-c2e17ed6-c76a-4578-bb91-0e49174c333e.png)


![METHOD MAX (MAX)](https://user-images.githubusercontent.com/119292258/235332360-bda2d56e-4ba4-4554-b3ea-9fe8ae5e4814.png)



![builten function](https://user-images.githubusercontent.com/119292258/235332365-4e020481-569f-41c9-b180-e924a95a51f8.png)











## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
