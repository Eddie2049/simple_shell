# Simple Shell

A basic UNIX command line interpreter written in C.

## Description

This project implements a simple shell based on the Thompson Shell that can execute basic commands. It's designed as a learning tool to understand the fundamentals of how shells work.

## Features

- Displays a prompt and waits for user input, command
- Executes single-word commands
- Handles command not found errors
- Supports the "end of file" condition (Ctrl+D)
- Hanling the command line with arguments
- Handle the PATH
- Support the exit features and the exit status
- Handle the Ctrl-C to not terminate the shell
- Handling the command seperator ;
- Handling && and || logical operators
- Handle variable replacements $? and $$
- Handle the comments #
- Support the history feature
- Support the file input

## Compilation

To compile the shell, use the following command:
- gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o simple_shell

## Usage

After compilation, run the shell with:
./simple_shell 

## Example
$ ./simple_shell
simple_shell> ls
[Contents of current directory]
simple_shell> pwd
/home/user/simple_shell
simple_shell> invalid_command
Error: command not found: invalid_command
simple_shell> [Ctrl+D]
$ 

## Contributors:

- Eddie W.
