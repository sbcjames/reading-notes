## Reading and Writing Files in Python

### What is a File?

- of 3 main parts:
  1. Header - Metadata about the contents of the file.
  1. Data - Contents of the file as written by the creator or editor.
  1. End of File - Special character that indicates end of file.

### File Paths

3 major parts:
  1. Folder Path - The file folder location on the file system where subsequent folders are separated by a forward slash / in Unix or backslash \ in Windows
  1. File Name - The actual name of the file
  1. Extension - The end of the file path pre-pended with a period (.) used to indicate the file type

### Opening and Closing a File in Python

- To open a file use the built-in function open() - open('dog_breeds.txt')
- To close a file there are 2 ways:
  1. Use the *try-finally block*.
  1. Use the *with* statement.

# Python Exceptions: An Introduction

**A Python program terminates as soon as it encounters an error.**

### Exceptions versus Syntax Errors

- *Syntax Errors* - Occur when the parser detects an incorrect statement.
- *Exception Errors* - Occur whenever syntactically correct Python code results in an error.

- raise allows you to throw an exception at any time.
- assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
- In the try clause, all statements are executed until an exception is encountered.
- except is used to catch and handle the exception(s) that are encountered in the try clause.
- else lets you code sections that should run only when no exceptions are encountered in the try clause.
- finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions

