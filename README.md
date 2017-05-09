# CodeCamp Notes

Lesson notes for LaunchCode's Immersive CodeCamp Summer 2017

## Parse Error
Parse errors are syntactical errors. Similar to gramatical errors in writing. 
Missing quotation marks, parens in the wrong place

**Example**
print(hello, world) 
instead of 
print("hello, world")

##Type Error
Type errors happen when you try to combine to opjects that are not compatible. Trying to add a string to an int for example.

**Example**
print(42 + twenty four)


##Name Error
Name errors occur when you use a variable before it has a value.

**Example**
x = a + b
a and b have not yet been defined, and the Name Error will occur.

##Value Error
Value errors occur when you pass a parameter to a funciton, and the function is expecting a type different from what you pass through it. 

**Example**
expecting a string input but having no input. or expecting an int and giving a float.

##Time Limit Error
Time Limit Errors occur when the program takes longer than expected to run. The Active Code expects every program to run under x number of seconds. If the program takes longer to run it will throw a Time Limit Error.

