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
#Program Developed by: KANNAN.S
#Register No: 212223230098

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
#Program Developed by: KANNAN.S
#Register No: 212223230098

def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program Developed by: KANNAN.S
#Register No: 212223230098

def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark
```



## Output:
i) # To find the maximum of marks using the list method sort.

![unit 3 ex 6 (i)](https://github.com/Kannan-S-coder/FindMaximum/assets/147120710/addcf5f6-d7ff-4104-8840-995b6f3288cb)

ii) # To find the maximum marks using the list method max().

![unit 3 ex 6 (ii)](https://github.com/Kannan-S-coder/FindMaximum/assets/147120710/96abc025-9205-453f-8664-8f7be1ceaa02)

iii) # To find the maximum marks without using builtin functions.

![unit 3 ex 6 (iii)](https://github.com/Kannan-S-coder/FindMaximum/assets/147120710/1d15fca1-56e2-48aa-845e-617a5690a6b7)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
