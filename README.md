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
Developed by: Lokhnath.J
RegisterNumber: 23004865
'''
def max_marks(marks):
    return(max(marks))
    


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Lokhnath.J
RegisterNumber: 23004865
'''
def max_marks(marks):
    return max(marks)
    


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
    for x in list1:
        if x > max:
            max = x
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-11-18 045408](https://github.com/Lokhnath10/FindMaximum/assets/138969918/c88d1081-3bdd-4c16-b81a-f18a00a5eafc)
![Screenshot 2023-11-18 045354](https://github.com/Lokhnath10/FindMaximum/assets/138969918/a624c541-0112-4e4c-b633-e23354ad322d)
![Screenshot 2023-11-18 045334](https://github.com/Lokhnath10/FindMaximum/assets/138969918/bb4f5e92-6a99-487c-9334-c7082b21e25e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
