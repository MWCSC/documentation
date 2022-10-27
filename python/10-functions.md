# Functions 

A functions is a block of code which only runs when it is called in the main program. Data, known as paramenters, can be passed into a function, and a function can return data as a result. A function can be used mutliple times by continuously calling it, this makes functions very useful in programming.

# Creating a function 

To create a function in Python, we use `def`. For example:

```py
def myfunction():
  print("This is a function")
```
# Calling a function

As stated before, to call a function we need to write the function followed by paranthesis in the main program, for example:

Code:
```py
def myfunction():
  print("This is a function")

#main program
myfunction()
```
Output:
```
This is a function
```

# Arguments/Paramentesrs

We can also pass data into a function, known as parameters (sometimes called arguments, the terms can be used interchangeably). To do this, we just add the arguments inside the parathensis in where we declare the function: `def addition(x, y)`, adding a comma whenever we need more than one. To pass data into the function, we just add said data in the main program where we call the function: `addition(1,2)`. It is important to have the same number of arguments in both the main program and the function. For example:

Input:
```py
def addition(x ,y):
  print(x+y)
  
#main program
addition(1, 2)
```

Output:
```
3
```
In the main function, num1 and num2 are declared, to pass these into our function, we just write the variables inside the paranthesis in where we call the function. Inside the function, we write the arguments x and y to signify the values that we want to be arguments. 

# Return

To return data from a function to the main program, we use the `return` syntax. For example:

Input:
```py
def addition(x ,y):
  sum = x+y
  return sum
  
#main program
value = addition(1, 2)
print(value)
```

Output:
```
3
```
As shown in the example above, we can use variables to hold the return value; functions can be called inside of a variable.

~ Ryan Alumkal
