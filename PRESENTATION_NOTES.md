# CS 119 Lecture Notes: Python Data Structures

## What this package contains
- CS119_List_Dict_Lecture.ipynb: 15-minute lecture notebook with built-in in-class exercises.
- Comparisons and integrated usage of list, dict, tuple, and object (`dataclass`).
- Student-life examples (boba budget, meme reactions, event check-ins).
- Lab references embedded in notebook and files in `labs/`.
- Slide metadata is already embedded per cell for slideshow workflows.

## Suggested live teaching script (15 minutes)
- 0-2 min: Data structure comparison mental model.
- 2-5 min: Mutability and key Python specs.
- 5-10 min: Student-life demos.
- 10-14 min: Two in-class exercises.
- 14-15 min: Bridge to labs and recap.

## Transitional passages (typical and reusable)
### From last lecture to this lecture
- "Last class, we focused on control flow: `if`, loops, and functions. Today, we answer a practical question: once your logic works, where do you store and organize real data?"
- "You already know how to repeat actions with loops; now we need containers to loop over. That's where list, tuple, dictionary, and objects come in."
- "Think of this as level-up day: same Python syntax skills, but now with data models that look like real student apps."

### From this lecture to next lecture
- "Today we chose the right container for data. Next class, we'll choose the right algorithm to process that data efficiently."
- "You can now model information with lists, dicts, tuples, and objects. Next lecture we will write reusable functions that transform these structures cleanly."
- "If today was about organizing data, next time is about scaling your code: decomposition, testing, and debugging patterns."

### Lab bridge line (end of class)
- "The labs are not new topics; they are the same patterns from class with slightly messier, more realistic inputs. If you can explain why you picked a structure, you are doing real computer science."

## In-class exercises included in notebook
- Exercise 1: Parking spot dedup with list operations.
- Exercise 2: Student profile object with class/dataclass.

## Lab assignment files
- labs/Lab_01_List_Warmup.md
- labs/Lab_02_Dict_Tracker.md
- labs/Lab_03_Integrated_Project.md

## Local/offline presentation options
### Option A: JupyterLab + RISE-style slideshow
1. Install once:
   pip install jupyterlab-rise
2. Launch JupyterLab in this folder.
3. Open the notebook and start slideshow mode from the RISE/JupyterLab command.

### Option B: Regular notebook view
- Present directly from notebook cells and run live code in sequence.
- This is the simplest and most reliable approach for offline teaching.

## Colab fallback
- Upload CS119_List_Dict_Lecture.ipynb to Google Colab.
- Run cells as-is.
- No external dependencies are required.

## Multi-OS note
- Notebook and labs are plain text/JSON/Markdown and work on Windows, macOS, and Linux.
- Use Python 3.10+ for best compatibility with the `dataclass` examples.

## Git + uv note
- Commit: `pyproject.toml`, `uv.lock`, notebook, and lab markdown files.
- Ignore: `.venv/` and `.python-version` (local machine specific).

## Teaching tips
- Before class, run all cells once to verify output.
- During class, intentionally make one small mistake (such as misspelling a key) and fix it live.
- Ask students to predict output before running each application demo.
