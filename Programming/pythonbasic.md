# Python Syntax Cheat Sheet

## Basics
- **Print**: `print("Hello World")` - Outputs a string to the console.
- **Input**: `input("What's your name")` - Prompts user input.
- **Comments**: Use `#` for comments. Example: `# This is a comment`.
- **Variables**: Assign values with `=`, e.g., `my_name = "Angela"`.
- **The `+=` Operator**: Adds to the existing value, e.g., `my_age += 4`.

## Data Types
- **Integers**: Whole numbers, e.g., `my_number = 354`.
- **Floating Point Numbers**: Decimal numbers, e.g., `my_float = 3.14159`.
- **Strings**: Text, e.g., `my_string = "Hello"`.
- **String Concatenation**: Combine strings, e.g., `"Hello" + "Angela"`.
- **Escaping a String**: Use `\\` to include quotes in a string, e.g., `speech = "She said: \\"Hi\\""`.

## Converting and Checking Data Types
- **Convert Data Types**: `float()`, `int()`, `str()`.
- **Check Data Type**: `type(variable)`.

## Errors
- **Name Error**: Variable not recognized, usually due to a typo.
- **Zero Division Error**: Dividing by zero is not allowed.
- **Syntax Error**: General error when code does not make sense to the interpreter.

## Functions
- **Creating Functions**: Define with `def`, e.g., `def my_function():`.
- **Calling Functions**: Trigger a function by name followed by `()`.
- **Functions with Inputs**: Pass parameters, e.g., `def add(n1, n2):`.
- **Functions with Outputs**: Use `return` to output a value.
- **Variable Scope**: Variables inside functions are local.
- **Keyword Arguments**: Provide arguments by name.

## Conditionals
- **If Statement**: Test conditions, e.g., `if n > 2:`.
- **Else Statement**: Execute if `if` condition is false.
- **Elif Statement**: Additional condition checks.
- **Logical Operators**: `not`, `and`, `or`.
- **Comparison Operators**: `>`, `<`, `>=`, `<=`, `==`, `!=`.

## Loops
- **For Loops**: Iterate over a sequence.
- **While Loops**: Repeat as long as a condition is true.

## Lists and Dictionaries
- **Lists**: Ordered collections, e.g., `my_list = [1, 2, 3]`.
- **Dictionaries**: Key-value pairs, e.g., `my_dict = {"name": "Angela", "age": 12}`.

## Modules
- **Importing Modules**: Use `import module_name`.
- **Aliasing Modules**: Use `as` to rename during import, e.g., `import random as r`.
- **Import Specific Items**: Use `from module_name import item`.

## Classes and Objects
- **Creating a Class**: Define with `class ClassName:`.
- **Creating an Object**: Instantiate with `object_name = ClassName()`.
- **Class Methods**: Functions within a class.
- **Class Variables**: Variables within a class.
- **The `__init__` Method**: Initialize objects with default values.
- **Class Inheritance**: Inherit properties and methods from another class using `class SubClass(ParentClass)`.
