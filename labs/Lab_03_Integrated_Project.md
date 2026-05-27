# Lab 03: Integrated Mini Project (CS 119)

## Theme
Build a tiny event app model for campus game night.

## Requirements
Use all four:
- list
- dict
- tuple
- object (class or dataclass)

## Starter idea
- `sessions` as a tuple of time slots.
- `queue` as a list of arriving students.
- `checkins` as a dictionary of student to visit count.
- `Event` object for event metadata.

## Tasks
1. Define an `Event` class/dataclass with fields: `name`, `room`, `host`.
2. Create `sessions` tuple with 3 time slots.
3. Create `queue` list with repeated names.
4. Build `checkins` dict from `queue`.
5. Print students who checked in more than once.
6. Print a summary line for the event.

## Extension (fun)
Give each student a random "energy level" from 1 to 5 and print a hype leaderboard.

## Reflection
In 4-6 lines, explain why each structure was chosen.

## Grading rubric (10 points)
- Correct use of each structure: 4
- Correct logic/output: 3
- Code style/readability: 2
- Reflection quality: 1
