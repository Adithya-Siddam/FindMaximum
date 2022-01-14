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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: S Adithya Chowdary
RegisterNumber: 21001700
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
max_marks([0,60,80,30,76,23])
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: S Adithya Chowdary
RegisterNumber: 21001700
'''
def max_marks(marks):
    maxi=max(marks)
    return maxi
```

iii) # To find the maximum marks without using builtin functions.
```
'''
Program to the maximum marks without using builtin functions.
Developed by: S Adithya Chowdary
RegisterNumber: 21001700
'''
def max_marks(list1):
    maxi = list1[0]
    for i in list1:
        if i>maxi:
            maxi=i
    return maxi
```
## Sample Input and Output
![Sample Input](/IMAGES/img1.png)
![Sample Input](/IMAGES/img2.png)
![Sample Input](/IMAGES/img3.png)
## Output:
![Output](/IMAGES/img4.png)
![Output](/IMAGES/img5.png)
![Output](/IMAGES/img6.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.