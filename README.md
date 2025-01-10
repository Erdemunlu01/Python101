# Python101

Hello,

In this document, I have compiled basic information for Python. Its contents are as follows;


# PYTHON 101 PART 1

## Print describtions

print(): The print() command allows us to print the things we write into, such as strings, integers, etc. or variables, dataframes, etc. to the screen.

## Variable describtions

Things that we assign to the content of certain information, which can be numbers, strings, dataframes, etc., are called variables.

## Data Type

There is a type of every information. Examples of these types are bool, integer, string. If we want to find out the type of information, we can find it with the type() command.

## Arithmatic operations

We can perform arithmatic operations with Python. These can be addition, subtraction, multiplication, division and mode. Python also recognizes process priority.

## String variable

In Python, we call information that is text a string. We can reach the values ​​we want among these. We can add two string values ​​and print them side by side.

## Boolean Variable

Boolean data type is a logical data type. We logically measure the condition in the command we wrote. It takes True and False as values.

## Collection Data Types

### List

The list data type holds information in the form of a series and is defined with square brackets. It can hold all kinds of data in its content.
Lists can be collected, information can be accessed and the information in them can be changed.

### Tuple

Tuple data types are similar to lists and are created with regular parentheses. The difference from lists is that the content of tuple data types cannot be changed.

### Dictionary

Dictionary data types are held by a counterpart. For example, noun: Erdem. Here, when we call the name value from the dictionary data, it will return us Erdem.
The content of dictionary data types can be changed and nested dictionaries can be made.



# PYTHON 101 PART 2

## If comand

The "if" command allows us to query the condition. Returns boolean(True, False) type data from the condition result. It performs operations as a result of this condition. The "if" command performs the action in its content if the condition is met. We can also specify what to do if the condition is not met with the "else" command. If we want to query more than one condition, we can add conditions with the "elif" command.

## for comand

The "for" command is a loop command. With this command, a loop will occur for a value we specify. With the loop, we determine how many times an action will be performed. Additionally, if we return a value in a series such as a list, we can perform an operation for each value in the list.

## while loop

The "while" loop allows us to perform the action we want as long as a certain condition is met. The loop ends when the condition is not met.

### enumerate

The enumerate() command allows us to retrieve values ​​by index in a list, tuple or dictionary. When used with the "for" loop, it returns each value in the list with its index.

### zip

The zip() command allows rotating two separate series together. Additionally, the combined elements are treated as a tuple.

### range

The range() command creates a series for the number we specify. For example, for range(3) it creates: 0,1,2. It can still create a series with a range, but it does not take the last element we specified in the range.

Note: If we want to make a list of a series, we can make it as [*"value"].

### break

The "break" command is used to exit the loop. It is usually used to break the infinite loop.

### continue

The "continue" command ensures that the code does not perform the next operation after the command and is used to go to the beginning of the loop.

### pass

The "Pass" command allows the code to pass after the command. It is generally used to prevent the code from getting errors during development.


# PYTHON 101 PART 3

## Functions

Functions in Python are a method by which we can assign the operations we want to perform to certain words and then call them. It is possible to produce functions that do not take values, but also functions that take values. In this way, it is possible to use the operations we want to perform in more than one place.

## Map, Filter, lamda

The Map() function is a function we use to apply a specific function to each value in a list.
The filter() function is a function we use to filter the values ​​in a specific list.
The lamda() function is used to create disposable functions in a single line and in a shorter form. It can contain arithmatic arguments, conditions, etc.

## input

The input() function is a function we use to receive external input. The value we get with this function is a string.

## Try, Except, Finally

"try" is used where we expect an error in a block of code. In case of an error, the code we wrote under the "except" statement will run and the code we wrote under the "try" statement will not work.
With "else" we indicate the code that will run if no error occurs.
"finally" kodu ile de her türlü çalışacak olan kodu belirtmiş oluruz.

try:
    # Code that may raise an exception
except [ErrorType]:
    # Code to execute if an exception occurs
else:
    # Code to execute if no exception occurs (optional)
finally:
    # Code to execute regardless of exceptions (optional)


# PYTHON 101 PART 4

## CLASS, OOP

The "Class" structure is considered the basis of object-oriented coding. Class structures can hold certain values ​​and fetch them when called. The "__init__" method performs object initialization. It can create cross-class inheritance. A "Class" can inherit the previous "Class".

## Moduls

The command that allows us to navigate through the file in Python starts with "%". We can use commands such as "%ls" and this command is the command that lists the files in the directory.

### OS

The "os" library allows us to navigate between files and directories, perform manipulations, etc. This library allows us to navigate within the computer where Python is installed. It has similar features to "Command Prompt (CMD)" on our computer.

## REgular Expression REGEX

"REGEX" library is a library used for filtering, matching, pattern finding, editing, etc. string values. It is a very flexible library.

^abc  # Matches 'abc' at the start of the string.
abc$  # Matches 'abc' at the end of the string.
[aeiou]  # Matches any of the vowels a, e, i, o, or u.
abc|def  # Matches either 'abc' or 'def'.
a*  # Matches zero or more occurrences of 'a'.
a+  # Matches one or more occurrences of 'a'.
a?  # Matches either no 'a' or one 'a'.
(abc)+  # Matches one or more occurrences of 'abc'.
\d  # Matches any digit from 0 to 9.
\D  # Matches any character that is not a digit.
\w  # Matches any letter, digit, or underscore.
\W  # Matches any character that is not a letter, digit, or underscore.
\s  # Matches any whitespace character.
\S  # Matches any character that is not a whitespace.
a{3}  # Matches 'aaa'.
a{3,}  # Matches three or more occurrences of 'a'.
a{3,5}  # Matches 3, 4, or 5 occurrences of 'a'.

## Random Module

"Random" kütüphanesi, Python'da bize rasgeleliği sağlar ve bu kütüphane ile rasgele sayı üretme ve rastgele seçme gibi işlemleri yapabiliriz.

## Math module

The "Math" library is the library that provides us with mathematics-related operations in Python. It contains mathematical functions (Combination, Root, Factorial, etc.)

## Collection modul

The "Collection" library is the library that allows us to analyze data structures more flexibly in Python. It is a library that allows us to develop data structures more flexibly.
The "Counter" command is a command that allows us to quickly count each value in a data structure, whether it is a single value or a word.

## Datetime

The "Datetime" library is a library in Python that allows us to work more flexibly on date and time information and to introduce this information into the programming language.

## Decorator

The "Decorator" function in Python makes a particular function run more efficiently. Generally, after this information is defined in a function, the function whose functionality we want to improve is called with the defined function.


# PYTHON 101 PART 5

## request response

"request" information is the information we send to the server, and we do this with the "request" library in Python. "response" is the information returned to us from the server in response to the information we send. If the 200 information comes to us from the server, this is a successful transaction and we have successfully communicated with the server.

## POST

The "POST" method is the method used when we want to send information to the server.  In this way, we can send information to the server and if we want, we can store this information on the server (database, etc.).

## Radar Chart

In this example, after sending information to the server, it returns us a graph. We send this information to the "image-charts.com" site.

## gui interface

We use "GUI (Graphical User Interface)" to create a visual interface in Python. This way we can design an interface that can interact with the user.

### tkinter

We can create a desktop application in Python with the "Tkinter" library.

Label: Displays text or graphical content.
Button: Creates clickable buttons for user interaction.
Entry: Provides a single-line text input.
Text: Allows multi-line text input.
Checkbutton: Adds checkboxes to indicate selected options.
Radiobutton: Adds radio buttons to select only one option from multiple choices.
Listbox: Presents options in a list format.
Canvas: Used for drawing graphics.
Frame: Acts as a container to group and organize other widgets.

## Sending Email

## Send email with attachment

We can send e-mail from Python with "SSL" and "smtplib" libraries. After logging into Python with our own user, we can send emails without or with attachments.

## read mail

In Python, we can perform operations such as reading and moving our e-mails with the "imap_tools" library. After logging in to Python with our own user, we can read our own e-mails.
