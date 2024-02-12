# Command Line Basics

## `pwd` (Print Working Directory)

The `pwd` command displays the file path from the root directory to the current working directory.

## `mkdir` (Make Directory)

The `mkdir` command is used to make a new directory in the filesystem according to its argument. If a file path is given, the new directory will be placed at the end. Otherwise, it will create a new directory in the current working directory.

## `ls` (List)

The `ls` command is used to list the contents of a directory. If no arguments are given, it will list the contents of the current working directory.

## `cd` (Change Directory)

The `cd` command is used to move throughout the filesystem of a computer. It accepts a variety of arguments:

- Full file paths.
- Names of children of the current directory.
- `..` the parent of the current directory.

## Filesystem Structure

A computer’s filesystem organizes the data stored by a computer, so that it can be easily retrieved by the user. Files are generally represented in a tree-like structure, in which any parent directory can have any number of children. The root directory is then found at the base of the tree.

## `touch` (Create New File)

The `touch` command creates a new file in the current working directory with the name provided.

## The Command Line

The command line allows a user to navigate the filesystem and run built-in programs or custom scripts. In Unix, the command line interface is called Bash, and the shell prompt is the `$`.

## Helper Commands

Helper commands for the command line include:

- `clear` to clear the terminal
- `tab` to autocomplete the line
- `↑` and `↓` to cycle through previous commands

## `cp` (Copy)

The `cp` command is used to copy files or directories.

## Command Options

Options can be used to modify the behavior of shell commands. Shell command options are commonly represented by a single letter preceded by a `-`. For example, `-l`, `-a`, and `-d` could all be options that follow a shell command.

## `mv` (Move)

The `mv` command is used to move a file into a directory.

## `rm` (Remove)

The `rm` command is used to delete files and directories. The `-r` flag deletes a directory and all of its files and directories (`rm -r`).

## `ls` List Command Options

The `ls` command is used to list the contents in a directory. It can be combined with the following command options:

- `-a`: lists all contents, including hidden files and directories.
- `-l`: lists all contents, in long format.
- `-t`: lists all contents, by the time they were last modified.

## Append Redirect Shell Command

The `>>` shell command is used to redirect the standard output of the command on the left and append (add) it to the end of the file on the right.

## Pipe Shell Command

The `|` command is called a pipe. It is used to pipe, or transfer, the standard output from the command on its left into the standard input of the command on its right.

## Redirecting Output

The `>` symbol is used to redirect output by taking the output from the command on the left and passing as input to the file on the right.

## `cat` (Display)

The `cat` command displays the contents of one or more files to the terminal.

## `grep` (Search)

The `grep` command is used to search files for lines that match a pattern and returns the results.

## Case Insensitive Search

The `grep` command with the `-i` option can be used to search files for lines that match a pattern, case insensitive, and returns the results.

## `grep -R` (Recursive Search)

The `grep` command has a `-R` option (`grep -R`) that searches all files in a directory, including its subdirectories, and outputs filenames and lines containing matched results.

## Command Line Redirection

On a command line, redirection is the process of using the input/output of a file or command to use it as an input for another file. It is similar but different from pipes, as it allows reading/writing from files instead of only commands.

## Command Line Environment

The environment of the command line refers to the settings and preferences of the current user. It enables users to set greetings, alias commands, variables, and much more.

## `env` (Shell Command)

For Unix-based systems like Mac OS and Linux (not Windows), the shell command `env` returns a list of environment variables for the current user.

## Alias

The `alias` command is used to assign commonly used commands to shortcuts (or aliases). The assigned commonly used command should be wrapped in double quotes.

## Environment Variables

Variables that can be used across terminal commands are called environment variables. They also hold information about the shell’s environment.

## Source Bash Profile

All the commands in `~/.bash_profile` are executed with the shell command `source ~/.bash_profile`. So when changes are made to `~/.bash_profile`, run this command to activate the changes in the current session.

## `history` Command

The `history` shell command is used to get a history of commands (also known as “events”) that were executed in the current session. The command also allows us to perform operations on this list of commands that have been executed, such as selecting or manipulating a command in the history.

## Export Command

The `export` command makes a given variable available to all child sessions initiated from the current session.

## `HOME` Environment Variable in Unix Systems

`HOME` is an environment variable present in command line environments. It is used to get the path to the current user’s home directory.
