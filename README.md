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
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python


def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    max_val = marks[0]
    for m in marks:
        if m > max_val:
            max_val = m
    return max_val

```



## Output:
<img width="955" height="374" alt="image" src="https://github.com/user-attachments/assets/48af33fe-2dc8-4e33-bc2b-5a9e4cfd6431" />
<img width="881" height="366" alt="image" src="https://github.com/user-attachments/assets/52555d8d-4ab4-4660-9f52-1baed087cabe" />
<img width="943" height="384" alt="image" src="https://github.com/user-attachments/assets/3b58b95b-374e-434e-9032-5a1b2430cdd6" />

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
