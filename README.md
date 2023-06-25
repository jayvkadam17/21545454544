QTQ: How can we store a single quote (') as a string in a variable?

To store a single quote (') as a string in a variable, you can use double quotes ("") to enclose the string. Here's an example:

```python
my_variable = "I'm a string with a single quote"
print(my_variable)
```

Output:
```
I'm a string with a single quote
```

By using double quotes to define the string, you can include a single quote within the string without causing any syntax errors.

Q/Q: Refer the below variable:
x = 'a(
Here, is x a character type or string type variable? Support your answer with an explanation.

In the given example, the variable `x` is a string type variable. In Python, strings can be defined using single quotes ('') or double quotes (""). So, when `x` is assigned the value 'a(', it represents a string containing the characters 'a('.

Q@Q: Apply the following functions on this variable: 'Welcome to Python foundation course'
- SP: `find('o')`
  This function returns the index of the first occurrence of the letter 'o' in the string. If 'o' is not found, it returns -1.

- .P: `count('o')`
  This function counts the number of occurrences of the letter 'o' in the string.

- ?P: `len()`
  This function returns the length of the string, which is the total number of characters in the string.

- P: Concatenation
  Concatenation is the process of combining two or more strings together. You can use the `+` operator to concatenate strings.

Here's an example of applying these functions on the given string:
```python
my_string = 'Welcome to Python foundation course'

# Applying functions
print(my_string.find('o'))  # Output: 4
print(my_string.count('o'))  # Output: 3
print(len(my_string))  # Output: 32
print(my_string + ' - Advanced')  # Output: Welcome to Python foundation course - Advanced
```

Q4Q: For the variable `wor = 'PanaJ1@T//56('`, calculate the following:
(a) Total number of alphabets in lowercase
(b) Total number of alphabets in uppercase
(c) Total number of numericals in the string

Here's the code to calculate the mentioned counts:
```python
wor = 'PanaJ1@T//56('

lowercase_count = sum(1 for char in wor if char.islower())
uppercase_count = sum(1 for char in wor if char.isupper())
numerical_count = sum(1 for char in wor if char.isnumeric())

print("Lowercase count:", lowercase_count)  # Output: 4
print("Uppercase count:", uppercase_count)  # Output: 3
print("Numerical count:", numerical_count)  # Output: 4
```

Q5Q: Write a code to store a numerical value inside a variable and then convert it into a string.

Here's an example code to achieve this:
```python
num = 123
num_str = str(num)
print(num_str)  # Output: "123"
print(type(num_str))  # Output: <class 'str'>
```

In this code, the variable `num` stores a numerical value, and then the `str()` function is used to convert it into a string. The resulting string is stored in the variable `num_str`. Finally, the string value and its type are printed.
