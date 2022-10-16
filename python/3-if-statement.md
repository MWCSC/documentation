# if Statement

The `if` statement is a staple statement among nearly every programming language. All it does it check a condition, and if the condition is true, the code within the statement is executed. Here's a breakdown:

```py
if (2 == 2):
    print('2 is equal to 2!')
```
This code simply checks `if` 2 is equal to 2. The part in the brackets `2 == 2` is called a condition. It can also be called a parameter, which matches what we will learn later on when dealing with functions.

Since 2 is equal to 2, the program would output `2 is equal to 2!`.

However, we can also use the `if` function to check multiple conditions at the same time. This can be acheived using the `and` keyword. Here's a breakdown:

```py
if (4 > 2 and 3 > 1):
    print('Hi there!')
```
The statement `Hi there!` will only be printed if both the conditions are true. Since 4 is greater than 2, and 3 is greater than 1, the statement would be printed.

We can also use the `if` function to check multiple conditions independently of each other. This can be acheived using the `or` keyword. Here's a breakdown:

```py
if (5 > 10 or 2 == 2):
    print('Hello!')
```
The statement `Hello!` will be printed if EITHER of the conditions are true. 5 is not greater than 10, but since 2 is equal to 2, the statement will be printed.

## Recap

|Keyword|Function|
|-------|--------|
|`and`|Check that multiple statements are true|
|`or`|Check if any statement is true|

~ Slate
