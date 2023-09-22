# 0x16. C - Simple Shell

## Table of Contents

- [Project Overview](#project-overview)
- [Team Members](#team-members)
- [Features](#features)
- [How to Build and Run](#how-to-build-and-run)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Project Overview

This is a group project for developing a simple UNIX command-line shell in the C programming language. The primary goal of this project is to create a functioning shell capable of executing basic commands, managing processes, and handling system calls. It is designed to mimic the behavior of a simplified Unix shell.

- **Project Type:** Group Project
- **Team Members:** Peninnah Kyakuwa

## Team Members
- [Peninnah Kyakuwa](https://github.com/KyakuwaPeninnah)

## Features

- Accept and execute basic Unix commands.
- Handle command lines with arguments.
- Manage the system's PATH.
- Implement built-in commands: `exit`, `env`, `cd`, `setenv`, `unsetenv`, `alias`.
- Handle logical operators `&&` and `||`.
- Variable replacement (`$?`, `$$`, etc.).
- Handle comments (`#`).
- Execute commands from a file as input.
- Prevent memory leaks.
- Interactive and non-interactive modes.

## How to Build and Run

1. Clone this repository to your local machine:

   ```bash
<<<<<<< HEAD
   git clone https://github.com/KyakuwaPeninnah/0x16-simple-shell.git
=======
   git clone https://github.com/your_username/simple_shell.git
   
2. Navigate to the project directory:
 cd 0x16-simple-shell

3. Compile the shell program:
   gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
   
4. Run the shell:
   ./hsh

5. Usage
* Start the shell by running ./hsh
* Enter commands and arguments when prompted.
* You can use built-in commands like exit, env, cd, etc.
* For more details on supported commands, see the project documentation.



