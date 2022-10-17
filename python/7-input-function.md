# Input function

The input function is incredibly useful for taking in user input at the command line. Here's a breakdown:

```py
name = input('What is your name?')
```

This code will ask for the users name and will pause the program until the user has inputted some value. Here is the output:

```
What is your name?|
```

The | is where the user's cursor is, for them to write a value. When they input something, it is assigned to the `name` variable. The `name` variable then contains the users input for the rest of the program.

**Note**: All input taken from a user is saved as a string. Even if the user inputs a different data type, the value is saved in string format. You must cast it to the expected value yourself, as shown below:

```py
age = input('What is your age?')
```
`Output: '12'` (string)

```py
age = int(input('What is your age?')
```
`Output: 12` (integer)

To learn more about data types, see the [Data Types Guide](../0-variables-data-types.md#data-types)

~ Slate
