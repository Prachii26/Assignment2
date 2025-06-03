# ASSIGNMENT 2
Module 3: Control Structures in Python

## Task 1

Check if a Number is Even or Odd.

Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.


### Code

```python
# takes input as integer
a=int(input("Enter a number: "))

#Checks if divisible by 2 then even else odd
if a%2==0 :
    print(a, " is an even number.")
else:
    print(a, " is an odd number.")
```

### Output
```
Enter a number: 7
7  is an odd number.
```
```
Enter a number: 12
12  is an even number.
```

## Task 2
Sum of Integers from 1 to 50 Using a Loop.

Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.

### Code

```python
# Set one counter var to store sum
sum=0
#Loop from 1 to 50
for i in range(1,51):
    sum=sum+i 
#Print the sum
print("The sum of numbers from 1 to 50 is: ",sum)
```

### Output
```
The sum of numbers from 1 to 50 is:  1275
```
