## Here is **my** python syntax, matching all the pseudocode syntax file's points:

### Variables (and Constants):
#### Assigning:
To assign a variable, use `variable = value`

All variables are to be in `camelCase` or `snake_case`

Constants are to be in `ALL_CAPS_SNAKE_CASE`

Variables are made global if they are declared at the start of the program. 

To use global variables in a subroutine, use the `global` keyword, as in the example below:
```python
variable = value

def function(argument):
    global variable
    return (argument * variable)
```

#### Casting:
To make a variable a string, use `variable = str(variable)`

To make a variable an integer, use `variable = int(variable)`

To make a variable a float, use `variable = float(variable)`

### Input and Output:
#### Input:
To ask for input with a message, and store the input in a variable, use `variable = input(message)`

#### Output:
To output a message, use `print(message)`

### Iteration:
#### For Loops:
To do something `n` times, use:
```python
for i in range(0,n+1):
    do_something()
```

#### While Loops:
To do something while a condition is not true, use:
```python
while condition != True:
    do_something()
```

#### Do-Until
There is no do-until structure in python. Sorry!

### Operators:
#### Mathematical:
To do addition, use `+`

To do subtraction, use `-`

To do multiplication, use `*`

To do division, use `/`

To do quotient, use `//`

To do modulus, use `%`

To do exponentiation, use `**`

#### Comparisons:
To do *equal to*, use `==`

To do *not equal to*, use `!=`

To do *less than*, use `<`

To do *less than or equal to*, use `<=`

To do *greater than*, use `>`

To do *greater than or equal to*, use `>=`

#### Logical:
To do *and*, use `and`

To do *or*, use `or`

To do *not*, use `not`

### Selection:
#### If/Else:
To use `if` statements, use the following structure:
```python
if conditionA:
    do_something()
elif conditionB:
    do_something_else()
else:
    do_something_else_else()
```

#### Switch/Case:
There is no switch/case structure in python. Sorry!

### String Handling:
#### Length:
To get the length of a string, use `len(string)`

#### Substrings:
To get a substring that starts at a specific postion 
and ends at a specific position, use `string[start:end]`

### Subroutines:
#### Functions
To define a function with arguments, start with `def name(argument):`

To return a value from a function, use `return value`

#### Procedures
To define a procedure with arguments, start with `def name(argument):`

#### Calling
To call a function or procedure on some data in the main program, use `name(data)`

### Arrays
To define an array called `name`, use `name = []`

To define a 2D array called `name`, use `name = []`

To call from a 2D array, use `name[index_in_main_array][index_in_array_inside_main_array]`

#### Comments
Start all single-line comments with `#`

Enclose all multi-line comments with `'''` at both ends
