# File Manipulation and Management

## Importance of File Manipulation

Files serve as long term storage for information. Every time you run a program, the memory is cleared once the program ends. Any data that you want to persist between program runs needs to be written to the hard disk. The best way to do this is to use files.

## Opening Files

```py
with open(filename, mode) as file:
```

``open`` - inbuilt function to open files
``filename`` - the name of the file to be opened and operated on
``mode`` - the mode used to open the file (more below)
``file`` - the variable we assign to the file when we open it

## File Modes

- ``w``
  - Write permissions
  - Wipes file before writing (If nothing is written, the file is wiped)
  - If file does not exist > Create file
- ``r``
  - Read permissions
  - Default mode
  - If file does not exist > Throw Error
- ``r+``
  - Read & Write permissions
  - Reads file before writing (If nothing is written, the file is wiped)
  - If file does not exist > Throw Error
- ``a``
  - Append permissions
  - Appends all data to the end of file after existing data
  - If file does not exist > Create file

## File Commands

- ``file.write(content)`` - Writes content to file
- ``file.read()`` - Reads entire file to string
- ``file.readlines()`` - Reads entire file to list, separated by newline
- ``file.append(content)`` - Appends content to file
- ``file.truncate()`` - truncates (cuts) a file down to desired length

**All commands must be nested under the opening of the file**

## OS module

The OS module is the operating system module.

It allows you to manipulate the operating system that the program is being run on.

It is very powerful, and has the ability to cause a lot of damage to the operating system.

It is the way we will be managing files.

### File Management with OS module

- ``os.move()`` - Move a file
- ``os.remove()`` - Delete a file
- ``os.rename()`` - Rename a file
- ``os.mkdir()`` - Create a folder
- ``os.rmdir()`` - Delete a folder

~ Slate
