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
Program to mark the maximum of marks using the list method sort
Developed by: 22008563
RegisterNumber: Suji.G
'''
def max_marks(marks):
    max1=marks[0]
    for i in marks:
        if i>max1:
            max1=i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])
   


```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Suji.G
RegisterNumber: 22008563
'''
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if i>max:
            max = i
    return max
max_marks([88,67,77,93,95,11,67,89,56,89])



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Suji.G
RegisterNumber:  22008563
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
max_marks([88,67,77,93,11,67,89,56,89])



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![m1](https://user-images.githubusercontent.com/119559822/214827587-6feae125-94af-46a5-8ed2-cbc80eb8225d.png)
![m2](https://user-images.githubusercontent.com/119559822/214827616-0dfdeda6-9767-4b32-9d69-83814d231251.png)
![m3](https://user-images.githubusercontent.com/119559822/214827651-d3097c6d-9c6b-41d8-9167-6540ec427f0b.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
