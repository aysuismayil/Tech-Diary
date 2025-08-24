# Python Basics Notes

This is a simple guide with explanations and examples of the main ideas in Python.  
It’s written in easy English to help beginners understand step by step.  

---

## Reserved Words

Every programming language has **reserved words** (keywords).  
They have special meaning in Python, so you cannot use them as variable names.

Examples: `import`, `assert`, `if`, `else`, `while`, `for`, `def`, `class`

👉 If Python sees `assert`, it knows it’s a command, not a name.

---

## Writing Programs: Lines and Paragraphs

A program is like a text file with many **lines**.  
Each line is an instruction, and together they make a paragraph (a program).

Example:

```python
x = 2
x = x + 2
print(x)
```
Steps:

Put number 2 into variable x.

Add 2 more and store it back into x.

Print the result → 4

Operators and Functions

+ is an operator (it adds things).

= is also an operator (it assigns values).

print() is a function. Inside the parentheses, we give it a parameter.

Example:
```python
y = 10
print(y + 5)
Output:
15
```
---

## Chevron Prompt in Python

This repository explains the **Chevron Prompt** in Python and provides examples.  
The chevron (`>>>`) is what you see in the Python interactive shell (REPL).

---

## What is Chevron Prompt?

When you start Python in interactive mode, you will see special prompts:

- `>>>` **Main prompt** — Python is ready for a new command.  
- `...` **Continuation prompt** — Python is waiting for the rest of your multi-line code.  


## Example

```pycon
>>> x = 10
>>> if x >= 10:
...     print("OK")
...
OK
>>> x * 2
20
# Tech-Diary
```

## Scripts and Python Programs

When programs get longer, we save them into a file.
Python files end with .py. These are called scripts or Python programs.

Example:
```python
hello.py
print("Hello, world!")
Run in terminal:
python hello.py
Output:
Hello, world!
```
---
A script is just a set of instructions saved in a file that Python can run.

Conditional Steps

Programs can also make decisions.
These are called conditional steps. They run only if something is true.

Example:
```python
x = 5

if x > 3:
    print("x is greater than 3")
else:
    print("x is not greater than 3")
Output:
x is greater than 3
```
---
Summary

Reserved words are special — don’t use them as names.

A program is made of lines, like sentences in a paragraph.

Operators (+, =) and functions (print) do the work.

The chevron prompt (>>>) is for testing small commands.

Save code in .py files to make scripts/programs.

Use conditional steps (if, else) to make decisions.

This is the foundation of Python programming 🚀
