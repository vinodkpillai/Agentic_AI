# My First Project

A simple Python "Hello World" program — my first project. It asks for your
name and prints a personalized greeting.

## What it does

When you run the program, it:

1. Asks you to type your name.
2. Waits for you to press **Enter**.
3. Prints a greeting like `Hello, Vinod!`

## Requirements

- [Python 3](https://www.python.org/downloads/) (no external libraries needed)

## How to run

From the project folder, run:

```bash
python3 hello.py
```

## Project structure

```
My_first_project/
├── hello.py     # the program (entry point)
└── README.md    # this file
```

## The code

```python
name = input("What is your name? ")
print(f"Hello, {name}!")
```

- `input()` reads the text you type and stores it in the variable `name`.
- The f-string `f"Hello, {name}!"` builds the greeting by dropping `name`
  straight into the text.
