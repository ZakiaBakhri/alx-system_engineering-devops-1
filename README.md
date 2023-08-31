# ALX School DevOps - Shell Permissions

Welcome to the ALX School DevOps Shell Permissions project repository. This repository contains scripts that perform various tasks related to manipulating file and directory permissions using shell commands.

## List of Scripts

1. **0-iam_betty**
   - Switches the current user to the user "betty" using the `su` command.

2. **1-who_am_i**
   - Prints the effective username of the current user.

3. **2-groups**
   - Prints all the groups the current user is a part of.

4. **3-new_owner**
   - Changes the owner of the file "hello" to the user "betty" using the `chown` command.

5. **4-empty**
   - Creates an empty file named "hello".

6. **5-execute**
   - Adds execute permission to the owner of the file "hello".

7. **6-multiple_permissions**
   - Adds execute permission to the owner and group owner, and read permission to other users for the file "hello".

8. **7-everybody**
   - Adds execution permission to the owner, group owner, and other users for the file "hello".

9. **8-James_Bond**
   - Sets permissions for the file "hello" as follows: no permission for the owner and group owner, and all permissions for other users.

10. **9-John_Doe**
    - Sets specific permissions for the file "hello".

11. **10-mirror_permissions**
    - Sets the same permissions for the file "hello" as those of the file "olleh".

12. **11-directories_permissions**
    - Adds execute permission to all subdirectories of the current directory for the owner, group owner, and other users.

13. **12-directory_permissions**
    - Creates a directory named "my_dir" with specific permissions.

14. **13-change_group**
    - Changes the group owner of the file "hello" to "school".

15. **100-change_owner_and_group**
    - Changes the owner to "vincent" and the group owner to "staff" for all files and directories in the working directory.

16. **101-symbolic_link_permissions**
    - Changes the owner and group owner of the symbolic link "_hello" to "vincent" and "staff" respectively.

17. **102-if_only**
    - Changes the owner of the file "hello" to "betty" only if it is currently owned by the user "guillaume".

18. **103-Star_Wars**
    - A script that plays the StarWars IV episode in the terminal.

## Author: OusamaTheCoder

These scripts are designed to help you understand and practice manipulating file and directory permissions using shell commands. Feel free to explore and use them to enhance your shell scripting skills.

=======
# Bash Project - Learning Shell Commands

This repository contains a collection of short Bash scripts that serve as a practical guide for understanding and using various shell commands in a Linux environment. Each script is designed to demonstrate a specific concept or command, all while adhering to the project's requirements for simplicity and clarity.

## Table of Contents

- [General](#general)
- [Navigation](#navigation)
- [Looking Around](#looking-around)
- [A Guided Tour](#a-guided-tour)
- [Manipulating Files](#manipulating-files)
- [Working with Commands](#working-with-commands)
- [Reading Man Pages](#reading-man-pages)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [LTS](#lts)

## General

In this section, you will find Bash scripts that cover fundamental concepts, including the shell, shebang, commands vs. built-ins, and basic usage of `help` and `man`.

## Navigation

Learn how to navigate the filesystem using commands like `cd`, `pwd`, and `ls`. Understand the significance of `.` and `..` directories, the working directory, root directory, and home directory.

## Looking Around

Explore commands like `ls`, `less`, and `file` for examining files and directories. Discover how to use options and arguments with commands, and grasp the long format of the `ls` command.

## A Guided Tour

Get familiar with the `ln` command for creating hard and symbolic links. Explore common and important directories, and understand the differences between hard and symbolic links.

## Manipulating Files

Learn how to perform file operations using commands like `cp`, `mv`, `rm`, and `mkdir`. Dive into wildcards and their usage for more efficient file manipulation.

## Working with Commands

Understand commands and their types, differentiate between external and built-in commands, and learn about aliases. Explore the purposes of `type`, `which`, `help`, and `man`.

## Reading Man Pages

Discover how to read and navigate man pages effectively. Understand man page sections and the numbering system for user commands, system calls, and library functions.

## Keyboard Shortcuts for Bash

Master common keyboard shortcuts for working efficiently in the Bash shell.

## LTS

Learn the meaning of LTS (Long Term Support) in the context of software releases.

---

**Note:** All scripts in this repository are exactly two lines

**Author**: Ousama Oujaber
