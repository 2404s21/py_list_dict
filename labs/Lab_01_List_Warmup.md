# Lab 01: List Basics For First-Time Python Students (CS 119)

## What you will practice
- Create a list.
- Access list items with indexes.
- Update a list with append/remove.
- Loop through a list.
- See that a list can hold different data types.

## Part A: Why 1 list is better than 5 variables
Compare these two approaches:

```python
# Option A: five separate variables
course1 = 'CS 003A'
course2 = 'CS 003B'
course3 = 'CS 008'
course4 = 'CS 020'
course5 = 'CS 021'

# Option B: one list variable
ml_path_courses = ['CS 003A', 'CS 003B', 'CS 008', 'CS 020', 'CS 021']
```

### Tasks
1. Print all five courses using the separate variables.
2. Print all five courses using the list variable.
3. Print only the first course and total course count using the list.
4. Write 1-2 sentences: why is the list version easier to manage?

## Part B: Basic list updates
Use this starter code:

```python
ml_path_courses = ['CS 003A', 'CS 003B', 'CS 008', 'CS 020', 'CS 021']
```

### Tasks
1. Print the first item and last item.
2. Add `'CS 025'` to the list.
3. Remove `'CS 020'`.
4. Print the updated list and the total number of items.

### Starter template
```python
ml_path_courses = ['CS 003A', 'CS 003B', 'CS 008', 'CS 020', 'CS 021']

# 1) first and last

# 2) add one item

# 3) remove one item

# 4) print final list and length
```

## Part C: Lists can store different types
Use this starter code:

```python
student_snapshot = ['Alex', 12, True, 3.4]
```

### Tasks
1. Print the list.
2. Print the type of each item using a loop.
3. Add one more item (for example `'CS Major'`).

### Starter template
```python
student_snapshot = ['Alex', 12, True, 3.4]

# print list

# loop and print each value + type

# append one more value and print again
```

## Quick check (2 minutes)
Write one sentence:
- When is a list a better choice than a single variable?

## Submission checklist
- Your code runs without errors.
- You included short comments for each step.
- You pasted output (or screenshots) for Part A and Part B.

## Want to learn more?
- Lists
	- Beginner: https://www.w3schools.com/python/python_lists.asp
	- Why indexing starts at 0: https://stackoverflow.com/questions/18283097/why-are-array-indexes-zero-based-in-most-programming-languages
	- More: https://docs.python.org/3/tutorial/datastructures.html#more-on-lists
- Dictionaries
	- Beginner: https://www.w3schools.com/python/python_dictionaries.asp
	- More: https://docs.python.org/3/tutorial/datastructures.html#dictionaries
