# Monty Repository README

## Table of Contents
1. [Introduction](#introduction)
2. [Files](#files)
   - [exec.c](#exec.c)
   - [freeStack.c](#freeStack.c)
   - [monty.h](#monty.h)
   - [monty.h.gch](#monty.h.gch)
   - [monty_main.c](#monty_main.c)
   - [monty_operators.c](#monty_operators.c)
   - [monty_operators2.c](#monty_operators2.c)
   - [monty_operators3.c](#monty_operators3.c)
   - [monty_operators4.c](#monty_operators4.c)
   - [node_addition.c](#node_addition.c)
   - [p_str.c](#p_str.c)
   - [pchar.c](#pchar.c)
   - [queue.c](#queue.c)
   - [rotl.c](#rotl.c)
   - [rotr.c](#rotr.c)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)

## Introduction
Welcome to the Monty repository! Monty is a simple interpreter for the Monty Bytecode files. The repository contains various files that together form the Monty interpreter. This README provides an overview of the files and instructions on installation, usage, and contributing.

## Files
### exec.c
Description: This file contains the main execution logic for the Monty interpreter.

### freeStack.c
Description: Implements functions related to freeing the memory allocated for the stack.

### monty.h
Description: Header file containing function prototypes, macros, and data structures used across different files.

### monty.h.gch
Description: Precompiled header file for monty.h

### monty_main.c
Description: Main entry point for the Monty interpreter.

### monty_operators.c
Description: Implements basic stack manipulation and arithmetic operations.

### monty_operators2.c
Description: Additional stack manipulation and arithmetic operations.

### monty_operators3.c
Description: More stack manipulation and arithmetic operations.

### monty_operators4.c
Description: Further stack manipulation and arithmetic operations.

### node_addition.c
Description: Functions for adding and manipulating nodes in the stack.

### p_str.c
Description: Implements the "pstr" opcode for printing the string starting at the top of the stack.

### pchar.c
Description: Implements the "pchar" opcode for printing the character at the top of the stack.

### queue.c
Description: Implements queue operations, allowing elements to be added to the back of the stack and removed from the front.

### rotl.c
Description: Implements the "rotl" opcode for rotating the stack to the top.

### rotr.c
Description: Implements the "rotr" opcode for rotating the stack to the bottom.

## Installation
Follow these steps to install and build the Monty interpreter:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/monty.git
   ```

2. Navigate to the Monty directory:
   ```bash
   cd monty
   ```

3. Compile the Monty interpreter:
   ```bash
   gcc -Wall -Werror -Wextra -pedantic *.c -o monty
   ```

## Usage
To use the Monty interpreter, follow these steps:

1. Run the Monty interpreter with a Monty Bytecode file:
   ```bash
   ./monty bytecode_file.m
   ```

2. Replace `bytecode_file.m` with the path to your Monty Bytecode file.

## Contributing
We welcome contributions to improve the Monty interpreter. If you would like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a meaningful name:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your commit message"
   ```
4. Push your changes to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request on the [Monty repository](https://github.com/your-username/monty) with a detailed description of your changes.

Thank you for contributing to Monty!