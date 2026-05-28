# Lab 03: Integrated Project (Beginner Version) (CS 119)

## Project theme
Build a small LACC CS learning-path helper.

## What you must use
- list
- dictionary
- tuple (brief)
- object (brief)

## Step 1: Create a list
Make a list of this week's tasks:

```python
tasks = ['review Python', 'go to office hours', 'ask 5 academic questions']
```

Task:
1. Print each task with a number using a loop.

## Step 2: Create a dictionary
Create a points dictionary for the same tasks:

```python
points = {
	'review Python': 0.2,
	'go to office hours': 0.5,
	'ask 5 academic questions': 0.3
}
```

Tasks:
1. Compute total points.
2. Print each task with its points.

## Step 3: Very brief tuple use
Create one tuple for a fixed office hour slot:

```python
office_hour_slot = ('Wednesday', '2:00 PM')
```

Task:
1. Print the tuple.

## Step 4: Very brief object use
Use a dataclass to model one student:

```python
from dataclasses import dataclass

@dataclass
class StudentCard:
	name: str
	major: str
```

Tasks:
1. Create one object.
2. Print the object.

## Full starter template
```python
from dataclasses import dataclass

# Step 1: list
tasks = ['review Python', 'go to office hours', 'ask 5 academic questions']

# Step 2: dictionary
points = {
	'review Python': 0.2,
	'go to office hours': 0.5,
	'ask 5 academic questions': 0.3
}

# Step 3: tuple (fixed info)
office_hour_slot = ('Wednesday', '2:00 PM')

# Step 4: object
@dataclass
class StudentCard:
	name: str
	major: str

student = StudentCard('Alex', 'CS')

# Your prints and loop logic below
```

## Reflection (short)
Write 3-4 lines:
1. Why did you use a list for tasks?
2. Why did you use a dictionary for points?
3. Why is tuple/object only brief here?

## How your work will be checked (10 points)
- Correct code execution: 4
- Correct use of list + dict: 3
- Brief tuple + object usage: 2
- Reflection: 1

## Want to learn more?
- Lists
	- Beginner: https://www.w3schools.com/python/python_lists.asp
	- More: https://docs.python.org/3/tutorial/datastructures.html#more-on-lists
- Dictionaries
	- Beginner: https://www.w3schools.com/python/python_dictionaries.asp
	- More: https://docs.python.org/3/tutorial/datastructures.html#dictionaries
- Tuples
	- Beginner: https://www.w3schools.com/python/python_tuples.asp
	- More: https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences
- Objects (classes/dataclasses)
	- Beginner: https://www.w3schools.com/python/python_classes.asp
	- More: https://docs.python.org/3/tutorial/classes.html
	- Dataclass reference: https://docs.python.org/3/library/dataclasses.html
