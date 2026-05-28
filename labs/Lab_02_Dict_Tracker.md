# Lab 02: Dictionary Basics For First-Time Python Students (CS 119)

## What you will practice
- Create dictionaries.
- Read and update values by key.
- Use `.get()` for safer lookups.
- Loop through key-value pairs.

## Part A: Weekly plan dictionary tracker
Use this starter code:

```python
points = {
	'CS 003A': 2,
	'CS 003B': 3,
	'CS 008': 2
}
```

### Tasks
1. Print the study hours for `'CS 003A'`.
2. Add one new course `'CS 020'` with `4`.
3. Update `'CS 008'` from `2` to `3`.
4. Print all course-hour pairs.

### Starter template
```python
points = {
	'CS 003A': 2,
	'CS 003B': 3,
	'CS 008': 2
}

# 1) print one value

# 2) add one key-value pair

# 3) update one value

# 4) loop and print key + value
```

## Part B: Course checkpoint dictionary
Use this starter code:

```python
checkpoint = {
	'quiz_1': 78,
	'quiz_2': 85,
	'project_1': 92
}
```

### Tasks
1. Print the score for `'project_1'`.
2. Use `.get()` to safely check `'quiz_3'` with default `'Not yet graded'`.
3. Print all checkpoint-score pairs.

### Starter template
```python
checkpoint = {
	'quiz_1': 78,
	'quiz_2': 85,
	'project_1': 92
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
	- Why indexing starts at 0: https://stackoverflow.com/questions/18283097/why-are-array-indexes-zero-based-in-most-programming-languages
	- More: https://docs.python.org/3/tutorial/datastructures.html#more-on-lists
- Dictionaries
	- Beginner: https://www.w3schools.com/python/python_dictionaries.asp
	- More: https://docs.python.org/3/tutorial/datastructures.html#dictionaries
