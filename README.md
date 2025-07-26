# assingment4
#task1
This Python program reads a text file named `sample.txt` and prints its contents line by line along with line numbers. It also handles errors gracefully if the file is not found.

## Features

- Opens and reads a text file (`sample.txt`)
- Prints each line with line numbers
- Handles `FileNotFoundError` if the file doesn't exist

## Code Functionality

- Uses `enumerate()` to number each line
- Uses `strip()` to remove extra spaces and newline characters
- Wraps the file operation in a `try-except` block

#task2
# File Write, Append, and Read Program in Python

This Python program demonstrates how to:
- Write user input to a text file (`output.txt`)
- Append additional text to the same file
- Read and display the final content of the file

## How It Works

1. The program opens `output.txt` in write mode and takes user input to write to the file.
2. Then it reopens the file in append mode to add more user input on a new line.
3. Finally, it opens the file in read mode to display the complete content.

## Technologies Used

- Python 3
- File Handling: `open()`, `write()`, `read()`, `close()`
