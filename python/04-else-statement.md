# Else & Elif Statements

### Else

`Else` statements work in tandem with `if` statements, and execute only if the `if` statement does not evaluate as true.

Here's a breakdown:

```py
if (2 == 3):
    print('Hello!')
else:
    print('Hi!')
```
This code checks if 2 is equal to 3. Since that does NOT evalute as being true, the code within the `if` statement is skipped, and the code within the `else` statement is executed.

**Notice**: While you can use an if statement without an else statement, you cannot use an else statement without using an if statement.

### Elif

`Elif` statements work between `else` and `if` statements. Code within `elif` statements only executes if the first `if` statement does not execute. `Elif` statements are checked and executed in the order that they are written. Here's a breakdown:

```py
if (2 == 3):
    print('Hello!')
elif (2 == 4):
    print('Hello again!')
elif (2 == 2):
    print('Hello for the third time!')
else:
    print('Hi!')
```
This code first checks if 2 is equal to 3. Since that does NOT evaluate as being true, it then checks if 2 is equal to 4. That also does NOT evaluate as being true, so it moves on to checking if 2 is equal to 2. This DOES evaluate as being true, so the program would print `Hello for the third time!`.

**Notice**: The else statement here is skipped, because the code found a condition (2 == 2) that is true before hitting the else condition.

~ Slate
