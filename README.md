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

DEVELOPED BY:SHIVAA PALANIYAPPAN V
REGISTER NUMBER:212223110050
i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark


```



## Output:
![image](https://github.com/shivaa-palaniyappan/FindMaximum/assets/146915611/2ee03f02-555f-4372-acb1-117e5b9cf79c)
![image](https://github.com/shivaa-palaniyappan/FindMaximum/assets/146915611/0057003a-fefb-4908-bb18-acf9e7d702b7)
![image](https://github.com/shivaa-palaniyappan/FindMaximum/assets/146915611/e4f84974-1f51-4d5a-b284-f7232dbed7b9)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
