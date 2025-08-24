# Course: Python for Eveybody - Trial
## What I learned today
### Computer Architecture Basics

- *CPU (Central Processing Unit):* the "brain" of the computer, executes instructions.  
- *Main Memory (RAM):* short-term working space, stores programs and data while running. Contents disappear when power is off.  
- *Secondary Memory (Disk/SSD):* long-term storage for programs and files, data stays after shutdown.  

### How they work together
1. A program (like Python code) is saved on *secondary memory*.  
2. When executed, it is loaded into *main memory (RAM)*.  
3. The *CPU* reads instructions from RAM and performs them step by step.  

### Python's role
- Python is a tool (programming language) used by programmers to tell the computer what to do.  
- It connects the "back side" (logic, code, processing) with the "front side" (what users see and use).  

### Analogy
- *Secondary memory = bookshelf*  
- *Main memory = desk*  
- *CPU = your brain*  
- *Python = the language of the books with instructions*

### Reserved Words
So if we start at vocabulary, the first thing we have in every programming language is what's called reserved words. Now, what do we mean by reserved words? Well, these are words that if we use these words, we must use them to mean the thing that Python expects them to mean. Another way to put that is we can't use them elsewhere. We can't make up a variable named import. We can't make a variable named assert; because if Python sees assert, it means something very specific to Python.Reserved Words in Python

In every programming language, we have what’s called reserved words (or keywords).
These are special words that have a specific meaning in Python and cannot be used for other purposes, such as naming variables.

If we use these words, we must use them in the way Python expects.
We cannot make up a variable named import or assert.
If Python sees assert, it knows it is a command with special meaning, not just a name.

## Writing a Python Program

When we write a program in Python, it’s like writing a text file made of lines.  
Each line is an instruction, and when we put these lines together, they make a whole program.  

For example:  

'''
x = 2
x = x + 2
print(x)
'''
First, we put the number 2 into the variable x.

Then we add 2 more and store the result back into x.

Finally, print(x) shows the result → 4.

### Operators and Functions

The plus (+) is called an operator.

The equal sign (=) is also an operator (it assigns values).

The word print is a function.
Inside the parentheses, we pass a parameter (in this case, x).
So when Python runs the code, it uses operators and functions to understand what we mean.

### Scripts and Python Programs

When we have more than just a few lines of code, it’s easier to put them into a **file** instead of typing everything directly into Python.  
We write the code in a text editor (like Atom, VS Code, or even Notepad) and save it.  

- A Python file ends with **`.py`**.  
- We call this file a **script** or a **Python program**.  
- Python runs the file from the beginning to the end, line by line.  

Text editors often help by showing colors (syntax highlighting), making code easier to read, and even pointing out mistakes.  

So, a **script** is just a set of instructions stored in a text file that Python can run.  

# Example

File: `hello.py`

'''
print("Hello, world!")
Run it in the terminal:
python hello.py
Output:
Hello, world!
'''

### Programming Basics: Flow of Control

A program is like a recipe — a sequence of steps that Python executes in order.

1. Sequence

Steps are executed one by one.
2. Conditional

Some steps are executed only if a condition is true.
3. Loops

Steps or groups of steps can be repeated.
4. Functions

A set of steps can be saved and reused multiple times.
Interactive vs Script:
	•	Interactive — type one command at a time; Python responds immediately.
	•	Script — save a sequence of steps in a .py file; Python executes them all.

Summary: Programs = sequences of steps, which can be conditional, repeated, or stored as functions.
