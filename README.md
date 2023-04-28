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
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    maxvalue=list1[0]
    for i in range(1,len(list1)):
        if list1[i]>maxvalue:
            maxvalue=list1[i]
    return maxvalue


``` 

## Output:
![method sort](https://user-images.githubusercontent.com/119292258/235069922-9812e654-d1ba-4026-ab78-e881dcb41bfd.png)

![method max](https://user-images.githubusercontent.com/119292258/235070016-10b61486-5f0b-4d47-a813-284b5371f5e8.png)


![builtin function](https://user-images.githubusercontent.com/119292258/235070040-eb584684-660a-43d5-8547-05cde188c4cd.png)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
