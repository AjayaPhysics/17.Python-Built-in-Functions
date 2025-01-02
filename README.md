# 17.Python-Built-in-Functions
Here’s a table that lists all 68 built-in functions in Python, their descriptions, and their uses:
# Python Built-in Functions

This table provides a comprehensive list of all 68 built-in functions in Python, along with their descriptions and example usage.

| **Function**        | **Description**                                                                 | **Example Usage**                          |
|---------------------|---------------------------------------------------------------------------------|-------------------------------------------|
| `abs()`             | Returns the absolute value of a number                                         | `abs(-5) -> 5`                            |
| `all()`             | Returns `True` if all elements in an iterable are `True`                      | `all([True, 1, "A"]) -> True`             |
| `any()`             | Returns `True` if any element in an iterable is `True`                        | `any([False, 0, "A"]) -> True`            |
| `ascii()`           | Returns a readable version of an object (escapes non-ASCII characters)        | `ascii('ñ') -> '\\xf1'`                   |
| `bin()`             | Converts an integer to a binary string                                         | `bin(10) -> '0b1010'`                     |
| `bool()`            | Converts a value to a boolean                                                 | `bool(0) -> False`                        |
| `bytearray()`       | Returns a mutable byte array                                                  | `bytearray("abc", "utf-8")`               |
| `bytes()`           | Returns an immutable byte object                                              | `bytes("abc", "utf-8")`                   |
| `callable()`        | Checks if the object is callable                                              | `callable(print) -> True`                 |
| `chr()`             | Converts an integer to its Unicode character                                  | `chr(97) -> 'a'`                          |
| `classmethod()`     | Converts a method into a class method                                         | `@classmethod` in class definitions       |
| `compile()`         | Compiles source into a code object for execution                              | `compile('x=5', '<string>', 'exec')`      |
| `complex()`         | Converts numbers or strings to a complex number                               | `complex(1, 2) -> (1+2j)`                 |
| `delattr()`         | Deletes an attribute from an object                                           | `delattr(obj, 'attr')`                    |
| `dict()`            | Creates a dictionary                                                         | `dict(a=1, b=2) -> {'a': 1, 'b': 2}`      |
| `dir()`             | Returns a list of attributes and methods of an object                        | `dir([]) -> ['append', 'clear', ...]`     |
| `divmod()`          | Returns quotient and remainder of division                                    | `divmod(10, 3) -> (3, 1)`                 |
| `enumerate()`       | Returns an enumerate object with index and value pairs                       | `list(enumerate(['a', 'b']))`             |
| `eval()`            | Evaluates a Python expression as a string                                    | `eval("2 + 2") -> 4`                      |
| `exec()`            | Executes dynamically created Python code                                      | `exec("x = 5; print(x)")`                 |
| `filter()`          | Filters elements of an iterable based on a function                          | `filter(lambda x: x > 2, [1, 2, 3])`      |
| `float()`           | Converts a value to a floating-point number                                  | `float("3.14") -> 3.14`                   |
| `format()`          | Formats a value according to a format specifier                              | `format(123, '04d') -> '0123'`            |
| `frozenset()`       | Returns an immutable set                                                     | `frozenset([1, 2, 3])`                    |
| `getattr()`         | Returns the value of a named attribute of an object                          | `getattr(obj, 'attr')`                    |
| `globals()`         | Returns the current global symbol table                                      | `globals()`                               |
| `hasattr()`         | Checks if an object has a specified attribute                                | `hasattr(obj, 'attr')`                    |
| `hash()`            | Returns the hash value of an object                                          | `hash("Python")`                          |
| `help()`            | Displays help information for a function/module                              | `help(print)`                             |
| `hex()`             | Converts an integer to a hexadecimal string                                  | `hex(255) -> '0xff'`                      |
| `id()`              | Returns the memory address of an object                                      | `id(123)`                                 |
| `input()`           | Reads input from the user                                                    | `name = input("Name: ")`                  |
| `int()`             | Converts a value to an integer                                               | `int("10") -> 10`                         |
| `isinstance()`      | Checks if an object is an instance of a class                                | `isinstance(5, int) -> True`              |
| `issubclass()`      | Checks if a class is a subclass of another class                             | `issubclass(bool, int) -> True`           |
| `iter()`            | Returns an iterator object                                                  | `iter([1, 2, 3])`                         |
| `len()`             | Returns the length of an object                                              | `len("abc") -> 3`                         |
| `list()`            | Converts an iterable to a list                                              | `list("abc") -> ['a', 'b', 'c']`          |
| `locals()`          | Returns the current local symbol table                                      | `locals()`                                |
| `map()`             | Applies a function to all items in an iterable                              | `map(str.upper, ['a', 'b'])`              |
| `max()`             | Returns the largest item in an iterable                                     | `max([1, 2, 3]) -> 3`                     |
| `memoryview()`      | Returns a memory view object                                                | `memoryview(b"hello")`                    |
| `min()`             | Returns the smallest item in an iterable                                    | `min([1, 2, 3]) -> 1`                     |
| `next()`            | Retrieves the next item from an iterator                                    | `next(iter([1, 2, 3])) -> 1`              |
| `object()`          | Returns a new featureless object                                            | `object()`                                |
| `oct()`             | Converts an integer to an octal string                                      | `oct(8) -> '0o10'`                        |
| `open()`            | Opens a file and returns a file object                                      | `open("file.txt", "r")`                   |
| `ord()`             | Converts a Unicode character to its integer representation                 | `ord('a') -> 97`                          |
| `pow()`             | Returns the power of a number                                               | `pow(2, 3) -> 8`                          |
| `print()`           | Prints to the console                                                      | `print("Hello")`                          |
| `property()`        | Creates a property for a class                                              | `property(fget=None, fset=None)`          |
| `range()`           | Returns a sequence of numbers                                               | `range(1, 5) -> [1, 2, 3, 4]`             |
| `repr()`            | Returns a string representation of an object                               | `repr(123) -> '123'`                      |
| `reversed()`        | Returns a reversed iterator                                                | `reversed([1, 2, 3])`                     |
| `round()`           | Rounds a number to a specified number of digits                            | `round(3.14159, 2) -> 3.14`               |
| `set()`             | Creates a set                                                              | `set([1, 2, 3]) -> {1, 2, 3}`             |
| `setattr()`         | Sets the value of a named attribute of an object                           | `setattr(obj, 'attr', value)`             |
| `slice()`           | Returns a slice object                                                     | `slice(1, 5, 2)`                          |
| `sorted()`          | Returns a sorted list                                                      | `sorted([3, 1, 2]) -> [1, 2, 3]`          |
| `staticmethod()`    | Defines a static method for a class                                        | `@staticmethod`                           |
| `str()`             | Converts a value to a string                                               | `str(123) -> '123'`                       |
| `sum()`             | Returns the sum of all items in an iterable                                | `sum([1, 2, 3]) -> 6`                     |
| `super()`           | Returns a proxy object for the parent class                                | `super().method()`                        |
| `tuple()`           | Converts an iterable to a tuple                                            | `tuple([1, 2, 3]) -> (1, 2, 3)`           |
| `type()`            | Returns the type of an object                                              | `type(123) -> <class 'int'>`              |
| `vars()`            | Returns the `__dict__` attribute of an object                              | `vars(obj)`                               |
| `zip()`             | Combines two or more iterables into tuples                                 | `zip([1, 2], ['a', 'b'])`                 |
| `__import__()`      | Imports a module                                                           | `__import__('os')`                        |

---

Feel free to copy and paste this Markdown into a `README.md` file. Let me know if you need further assistance! 🚀
