# Print Function 

The `print()` function prints a specified message to the screen

The message can be a string, or any other object, which will then be outputed for the user.

# Passing a string message directly to `print()`

Code: `print("Hello World")`

Output: `Hello World`
 
Messages in the `"" ""` (quotation marks) are printed literally.

# Passing a string message through a variable

Code: 
```
message = "Hello World"
print(message)
```
Output: `Hello World`

Code: 
```
message = 5
print(message)
```
Output: `5` 

The stored value in the variable, in this case the variable `message` holds the value `5`, is outputed by coding `print(message)`.

***NOTICE:*** coding `print("message")` will **NOT** output `5`, instead, it will output `message` as any value in the `"" ""` are printed literally.

# Using **string(s)** and **variable(s)** in `print()`

Code: 
```
a = 5 
print("a=", a)
```

Output: `a= 5`

The `,` (comma) can be used to combine values in the `print()` function. A space will be used between the messages.

Code: 
```
a = 5
print("a="+a)
```

Output: `a=5`

Notice the difference between the `,`(comma) and the `+`(addition symbol). `+`  combines values without the use of a space inbetween.

# Mathematical Operations in `print()`

The `print()` function also allows mathematical operations to be done in the function

Code:
```
print(5+5)
```
Output: `10`

Similarly, `-`, `*`, `/`, and other math operations can be used similarly. For more information on math operations, view [In-built Math Functions](./2-inbuilt-math-functions.md)

~Ryan Alumkal
