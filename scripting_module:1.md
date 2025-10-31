# Module 1: Getting Started with Shell & Bash
## Concepts:
What is a Shell? What is Bash?
What is a Shell?
- A shell is a command-line interpreter that provides a user interface for the operating system's kernel. It allows users to interact with the os by typi

In simple terms:
- The shell takes your commands and tells the operating system what to do.
- You type commands → shell interprets them → OS performs actions.

## common Unix/Linux Shells

|Shell | Description                                                                                                     |
|------|-----------------------------------------------------------------------------------------------------------------|
| sh   | Original Bourne Shell – the standard Unix shell.                                                              |
| bash | Bourne Again Shell – enhanced and backward-compatible version of sh.                                          | 
| zsh  | Z Shell – modern shell with features like auto-suggestions and plugin support.                                |
| fish | Friendly Interactive Shell – known for its user-friendly design and syntax highlighting.                      |
| dash | Debian Almquist Shell – lightweight and fast; used by some Linux systems (e.g., Debian/Ubuntu) for scripting. |

** What is Bash? **
- Bash stands for Bourne-Again SHell.
- It is a widely used shell on Linux and macos systems.
- Bash is both an interactive command interpreter and a scripting language 

### Features of Bash:
- Command history
- Tab completion
- Scripting capabilities
- Customizable environment
- Supports variables, 1oops, conditionals, functions
- Portable across many Unix-like systems

### Example Bash Command:
H
echo "Hello from Bash!"
Example Bash Script (hello.sh):
#l/bin/bash
echo "This script is running in Bash!"
...
- How to Check which Shell You're Using
Run this in your terminal:

# How to Check Which Shell You're Using
Or check which shell is currently active:
C Coursera | Online C...
Hom
ps -p
-o comm=
Changing Your Default Shell
You can change your default shell using the chsh command:
chsh -s /bin/zsh
Make sure the desired shell is installed before switching.
# Terminal vs Shell vs Bash - What's the Difference?

| Term | Description |
|------|--------------|
| Terminal | A program that gives you access to the shell. It’s the interface where you type commands (e.g., GNOME Terminal, **iTerm2, **Windows Terminal). |
| Shell | A command-line interpreter that processes commands typed in the terminal and communicates with the operating system. Examples include sh, bash, zsh, fish, etc. |
| Bash | A specific and widely used shell called Bourne Again Shell. It’s backward-compatible with the original Bourne shell (sh) and includes enhanced features. |

## Analogy
Think of it like this:
- The terminal is your steering wheel.
- The shell (like Bash) is the engine that makes the car move.
I
- You type commands into the terminal, which passes them to the *shell (e.g-, Bash), and then the OS does the work.

#Example Commands in Bash via Terminal  

echo "Hello from Bash!" # This runs in the shell (Bash), through the terminal

## Summary Table

| Concept   | Type         | Purpose |
|------------|--------------|----------|
| *Terminal* | Application | Provides a window/interface to interact with the shell |
| *Shell*     | Interpreter | Accepts and executes commands entered by the user |
| *Bash*      | Shell       | A popular shell with advanced features and scripting capabilities |
