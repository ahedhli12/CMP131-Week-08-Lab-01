# CMP 131 – Python Programming

> **Required file location:** Keep every Python file directly in the repository root. Do not create a `src` folder.

## Week 8 – Lab 1: Sales Bar Chart and Loop Patterns

**Total Points: 100**

- Program 1: Sales Bar Chart — 50 points
- Program 2: Increasing and Decreasing Patterns — 50 points

## Learning Objectives

After completing this lab, students should be able to:

- Accept and convert numeric user input.
- Use loops to repeat input and output operations.
- Use counter-controlled loops.
- Use nested loops to create visual patterns.
- Use integer division to convert numeric amounts into chart symbols.
- Control whether output continues on the same line or moves to a new line.
- Validate numeric input.
- Display information clearly and consistently.
- Test programs using different input values.
- Use comments to explain major sections.

## Assignment Overview

Create two separate Python programs:

1. `sales_bar_chart.py` — ask for the daily sales of five stores and display a horizontal bar chart where each asterisk represents $100 in sales.
2. `loop_patterns.py` — use loops to display an increasing plus-sign pattern and a decreasing plus-sign pattern.

The instructor is not providing completed Python code or an exact output design. Students must design, write, and test their own programs.

# Program 1: Sales Bar Chart

**Points: 50**

Create `sales_bar_chart.py`.

Your program must:

- Display a descriptive title.
- Ask the user to enter today's sales for five stores.
- Convert each sales value to an appropriate numeric data type.
- Reject negative sales values and ask again.
- Store or process all five valid sales amounts.
- Display a horizontal bar chart comparing the five stores.
- Use one asterisk for every $100 in sales.
- Use integer division to determine how many asterisks to display.
- Clearly label each store.
- Use a loop instead of writing five separate chart statements.

Examples of the required chart scale:

- $100 represents 1 asterisk.
- $500 represents 5 asterisks.
- $1,000 represents 10 asterisks.
- $1,900 represents 19 asterisks.

Test the program using several different sales values, including 0, values below $100, values exactly divisible by $100, values greater than $1,000, and an invalid negative amount.

# Program 2: Increasing and Decreasing Patterns

**Points: 50**

Create `loop_patterns.py`.

The program must display two separate patterns using plus signs.

## Pattern A: Increasing

Use loops to display rows that increase from:

- 1 plus sign
- 2 plus signs
- 3 plus signs
- ...
- 10 plus signs

Do not type all ten rows manually. The pattern must be produced by loops.

## Pattern B: Decreasing

Use loops to display rows that decrease from:

- 10 plus signs
- 9 plus signs
- 8 plus signs
- ...
- 1 plus sign

Again, do not type all ten rows manually.

Your program should:

- Display a descriptive title or labels for the two patterns.
- Use an outer loop to control the rows.
- Use a nested loop or equivalent loop-based approach to control the number of plus signs.
- Keep each row on one line.
- Move to a new line after each completed row.
- Display all rows in the correct order.

# Code Comments

Each Python file must include a comment header containing:

- Student name
- Course number
- Week number
- Lab number
- Assignment title
- Date

Use comments to identify major sections such as variable initialization, user input, validation, loops, calculations, and output.

# General Requirements

- Use meaningful variable names.
- Use loops where required.
- Do not manually duplicate repeated operations that are intended to be loop-based.
- Keep all Python files directly in the repository root.
- Test both programs carefully.
- Make sure both programs run without errors.
- Follow `AI-Use-Policy.md`.
- Complete `AI-Use-Report.md` honestly.

# Submission Requirements

Your repository must include:

- `CMP131-Week-08-Lab-01.md`
- `sales_bar_chart.py`
- `loop_patterns.py`
- `AI-Use-Policy.md`
- `AI-Use-Report.md`

Before submitting:

1. Run and test both programs.
2. Confirm filenames are correct.
3. Confirm all required Python files are in the repository root.
4. Complete the AI-use report.
5. Commit and push your latest work.
6. Verify the newest files on GitHub.
7. Submit through Blackboard Ultra as directed.

**Do not push your work to the instructor's starter repository.**
