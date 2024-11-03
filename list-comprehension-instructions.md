## Python: List Comprehension

### Objective

Learn how to use **list comprehension**, a shortcut and newer way to generate a new Python list

### Overview 
- List comprehension lets you fill your new list with values that Python has manipulated or modified for you in some way
- For example, you could take a list of numbers 1 - 10 and tell Python to multiply each number in the list by 100
- Using list comprehension, you can add the result of each calculation to a NEW list, which you could then print or modify further, if desired

### Related Resources

- YouTube: [Bro Code / List Comprehension](https://youtu.be/fcLDzKH_5XM?feature=shared)

### Coding Tasks

#### Title Case Names

- Take a list of 5 - 6 last names and use list comprehension to make a new list of names all in title case


#### Filtered Lowercase Names 

- In your **original list** (`students`), you should have 5 - 7 first names, all written in UPPERCASE
- Use list comprehension to create a new list of student names in lowercase
- Add an `if` statement to your list comprehension that checks the length of EACH student name; if the length of the name is GREATER THAN OR EQUAL TO 4 characters, Python should include the name in the new list of lowercase names
- Finally, print the new list of lowercase names
- See the `list_comprehension_demo1.py` file for examples of how to get started with list comprehension

#### Inches to Centimeters

- Define a list named `inches` and add to it 7 - 8 numbers that represent different lengths in inches
```python
inches = [14, 20, 36, 40]
```
- Use list comprehension to generate a NEW list named `centimeters`
- Your new list should contain the equivalent length **in centimeters**
- For example, using the `inches` list above, what would be the equivalent of 14 inches **in centimeters**?
- Print both the original `inches` list and your new `centimeters` list
- Also add print statements that identify which list is which in your output