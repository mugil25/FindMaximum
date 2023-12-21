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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Mugil
RegisterNumber: 23008346
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    #Write your code here
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Mugil
RegisterNumber: 23008346
'''
def max_marks(marks):
    max1=max(marks)
    return max1
    # write your code here



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Mugil
RegisterNumber: 23008346
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    # write your code here



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
1.Write a program to mark the maximum of marks using the list method sort.
![image](https://github.com/mugil25/FindMaximum/assets/148515771/ad7c37b5-c914-4510-95fe-a0c3a8d89de1)
2.Write a program to find the maximum marks using the list method max().
![image](https://github.com/mugil25/FindMaximum/assets/148515771/65a58146-d6ae-4c37-b6cc-5627687f63cf)
3.Write a program to find the maximum marks without using builtin functions.
![image](https://github.com/mugil25/FindMaximum/assets/148515771/cd6ccccf-3ab7-41d2-bc46-2cfe8331fd16)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
