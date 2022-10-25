# While loops

While loops work similarly to for loops, but they continue to run as long as a condition is true.

Here's a breakdown:

```py
condition = True

while condition:
    print('Hello World!')
```
**Note**: When checking if a variable is true, you do not need to use ``== True``, you can simply just write the name of the variable, as shown above.

This code will run forever, and constantly output print, because `condition` is defined as true, and the while loop is checking if `condition` is True.

However, if we change the condition, the loop will stop. Here's a breakdown:

```py
condition = True
value = 0

while condition:
    value = value + 1
    if value == 5:
        condition = False
```
This code implements concepts we learned in multiple previous guides. For more help on [variables](./0-variables-data-types.md) and [if statements](./3-if-statements.md), read their specific guides.

In the above code, the loop would continue to run until the value eventually reaches 5, where the condition would be changed to `False`, and the loop would not run after that. This is the same as using a `for` loop with a range of 5.

~ Slate
