### For Loop

Loops greatly reduce the amount of repetitive code you need to write. A `for` loop loops through a segment of code *for* the duration specified.

### Using for loops with a specified number

Using a for loop with a specified number means that the code will be executed exactly that many times. Here's a breakdown:

```py
for i in range(5):
    print('Hello!')
```
This code will print `Hello!` 5 times on the screen.

#### range

The range keyword loops over all the numbers until the specified one. It can take in multiple parameters. Here is a breakdown of the function:

`range(start, end, increment)`

The first number is where the range begins, and the second number is where the range ends. The final number is how the range should increase each time.

**Note**: The `start` and `increment` options are optional. You can choose to specify one or the other, or both. If you only put one number in parentheses, python will set that number as the `end` option.

### Using for loops over a list

If you have a list, you can loop through each value in the list. Here's a breakdown:

```py
fruits = ['apples', 'bananas', 'oranges']

for fruit in fruits:
    print(fruit)
```
This code will loop through each fruit in the fruits loop, and will print it out.

~ Slate
