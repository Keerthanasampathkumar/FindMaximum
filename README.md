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
Developed by: KEERTHANA S 
RegisterNumber: 22009006
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: KEERTHANA S
RegisterNumber: 22009006
'''
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: KEERTHANA S
RegisterNumber: 22009006
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
### Input:
![output](./img/max_marks1.jpg) 

![s2](https://user-images.githubusercontent.com/119477890/214069199-4164214d-f10d-4038-b7fd-f93f57678be5.png)

![s3](https://user-images.githubusercontent.com/119477890/214069254-00914e94-060b-4963-afc4-7b00217ce70f.png)

## Output:
![p1](https://user-images.githubusercontent.com/119477890/214069392-0135d343-31d4-42fb-ad5b-4bc98c667aa6.png)

![p1](https://user-images.githubusercontent.com/119477890/214069420-353542ce-5d56-4890-9382-9d94d123d0dc.png)

![p1](https://user-images.githubusercontent.com/119477890/214069438-47bf5161-41a0-40e2-b448-5d22ea6aea86.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
