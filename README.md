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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark
```



## Output:
![Screenshot 2024-04-06 210502](https://github.com/SanjaiOfficial/FindMaximum/assets/151763180/07022f6b-0693-497c-995d-e72648b4f3f1)
![Screenshot 2024-04-06 210515](https://github.com/SanjaiOfficial/FindMaximum/assets/151763180/8e21b828-1b35-45d1-ae51-0a2fccfad3e6)
![Screenshot 2024-04-06 210533](https://github.com/SanjaiOfficial/FindMaximum/assets/151763180/ddd82f5b-02b9-486f-8302-437e5ad2aa55)
![Screenshot 2024-04-06 210543](https://github.com/SanjaiOfficial/FindMaximum/assets/151763180/e35d8d73-7fd4-4786-ae08-8cc06922bfab)
![Screenshot 2024-04-06 210554](https://github.com/SanjaiOfficial/FindMaximum/assets/151763180/30e8d951-6386-4b34-8d07-f3e47c23ecba)
![Screenshot 2024-04-06 210605](https://github.com/SanjaiOfficial/FindMaximum/assets/151763180/3423c148-6826-4231-bd28-9038f95ea857)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
