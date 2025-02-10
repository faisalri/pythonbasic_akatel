## Built-in Functions in Python

Python provides several built-in functions that are always available for use. These functions help perform common tasks and operations. Here are some examples:

### Common Built-in Functions

1. `print()`: Outputs data to the console.
2. `len()`: Returns the length of an object.
3. `type()`: Returns the type of an object.
4. `int()`, `float()`, `str()`: Convert values to an integer, float, or string, respectively.
5. `input()`: Reads input from the user.
6. `sum()`: Sums the items of an iterable.
7. `max()`, `min()`: Return the maximum or minimum value of an iterable.
8. `sorted()`: Returns a sorted list of the specified iterable.

### Example Usage

```python
# Using print() to display a message
print("Hello, World!")

# Using len() to get the length of a list
numbers = [1, 2, 3, 4, 5]
print(len(numbers))  # Output: 5

# Using type() to get the type of a variable
print(type(numbers))  # Output: <class 'list'>

# Converting values
print(int("10"))  # Output: 10
print(float("10.5"))  # Output: 10.5
print(str(10))  # Output: "10"

# Reading user input
name = input("Enter your name: ")
print("Hello, " + name)

# Summing values
print(sum(numbers))  # Output: 15

# Finding maximum and minimum values
print(max(numbers))  # Output: 5
print(min(numbers))  # Output: 1

# Sorting a list
print(sorted(numbers, reverse=True))  # Output: [5, 4, 3, 2, 1]
```

These are just a few examples of the many built-in functions available in Python. For a complete list, refer to the [Python documentation](https://docs.python.org/3/library/functions.html).