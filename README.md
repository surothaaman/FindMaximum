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
Developed by:Surothaaman R
RegisterNumber:23008504
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max

```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 

def max_marks(marks):
    max_marks=max(marks)
    return max_marks

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Output:
i) # maximum of marks using the list method sort.
![Screenshot (86)](https://github.com/surothaaman/FindMaximum/assets/133313653/bfab2bde-6fe0-40a0-ac75-286badc552f5)
ii) # maximum marks using the list method max().
![Screenshot (87)](https://github.com/surothaaman/FindMaximum/assets/133313653/6468ebea-629a-4659-8c7d-b21d2acdfdc1)
iii) # maximum marks without using builtin functions.
![Screenshot (88)](https://github.com/surothaaman/FindMaximum/assets/133313653/f087ee34-1bb1-4a73-b2ed-45e4c4894696)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
