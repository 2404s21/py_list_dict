# Lab 02: Dictionary Basics For First-Time Python Students (CS 119)

## What you will practice
- Create dictionaries.
- Read and update values by key.
- Use `.get()` for safer lookups.
- Loop through key-value pairs.

## Part A: Contribution points tracker
Use this starter code:

```python
points = {
	'go to office hours': 0.5,
	'ask 5 academic questions': 0.3,
	'share one resource': 0.2
}
```

### Tasks
1. Print the points for `'go to office hours'`.
2. Add one new task: `'tutor a classmate'` with `0.4`.
3. Increase `'share one resource'` from `0.2` to `0.25`.
4. Print all tasks and points.

### Starter template
```python
points = {
	'go to office hours': 0.5,
	'ask 5 academic questions': 0.3,
	'share one resource': 0.2
}

# 1) print one value

# 2) add one key-value pair

# 3) update one value

# 4) loop and print key + value
```

## Part B: CS pathway salary dictionary (practice data)
Use this starter code:

```python
median_salary = {
	'Data Analyst': 78000,
	'Software Engineer': 130000,
	'ML Engineer': 145000
}
```

### Tasks
1. Print the salary for `'ML Engineer'`.
2. Use `.get()` to safely check `'AI Researcher'` with default `'N/A'`.
3. Print all roles and salaries.

### Starter template
```python
median_salary = {
	'Data Analyst': 78000,
	'Software Engineer': 130000,
	'ML Engineer': 145000
}

# 1) direct lookup

# 2) safe lookup with .get

# 3) loop through dictionary
```

## Mini challenge
Given this list, build a frequency dictionary:

```python
topics = ['list', 'dict', 'list', 'loop', 'dict', 'dict']
```

## Reflection
Write 2-3 sentences:
- When would you choose a dictionary instead of a list?

## Submission checklist
- Your code runs without errors.
- You included comments.
- You included output for both parts.

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
