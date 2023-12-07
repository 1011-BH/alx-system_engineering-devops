# 0x01. Shell, permissions

This project focuses on Shell scripting and managing permissions in a Linux environment using Bash scripts.

## Project Details

- **By:** Julien Barbier
- **Weight:** 1
- **Start:** Dec 7, 2023 6:00 AM
- **End:** Dec 8, 2023 6:00 AM
- **Auto Review:** Will be launched at the deadline

## Concepts

For this project, you're expected to understand the following concepts:
- Permissions
- Commands: `chmod`, `sudo`, `su`, `chown`, `chgrp`
- Linux file permissions
- Representing permission sets as a single digit
- Changing permissions, owner, and group of a file
- Running commands with root privileges
- Changing user ID or becoming a superuser

## Resources

### Read/Watch:
- [Permissions](https://linuxize.com/post/linux-file-permissions/)
- Man or Help:
  - `chmod`
  - `sudo`
  - `su`
  - `chown`
  - `chgrp`
  - `id`
  - `groups`
  - `whoami`
  - `adduser`
  - `useradd`
  - `addgroup`

### Learning Objectives

By the end of this project, you're expected to be able to explain:
- What the mentioned commands do
- Linux file permission representation
- Changing permissions, owner, and group of files
- Running commands with root privileges
- Creating users and groups
- Printing user and group IDs and related information

## Requirements

- **Editors:** vi, vim, emacs
- Scripts tested on Ubuntu 20.04 LTS
- Exactly two lines for each script (`wc -l file` should print 2)
- Files ending with a new line
- The first line of each file: `#!/bin/bash`
- A README.md explaining each script's functionality
- Prohibited: backticks, &&, ||, or ;
- All files executable

## Tasks

### Task 0: My name is Betty
- Script: [0-iam_betty](./0x01-shell_permissions/0-iam_betty)
- Description: Switches the current user to the user betty

### Task 1: Who am I
- Script: [1-who_am_i](./0x01-shell_permissions/1-who_am_i)
- Description: Prints the effective username of the current user

### Task 2: Groups
- Script: [2-groups](./0x01-shell_permissions/2-groups)
- Description: Prints all groups the current user is part of

### Task 3: New owner
- Script: [3-new_owner](./0x01-shell_permissions/3-new_owner)
- Description: Changes the owner of the file hello to the user betty

### Task 4: Empty!
- Script: [4-empty](./0x01-shell_permissions/4-empty)
- Description: Creates an empty file called hello

### Task 5: Execute
- Script: [5-execute](./0x01-shell_permissions/5-execute)
- Description: Adds execute permission to the owner of the file hello

### Task 6: Multiple permissions
- Script: [6-multiple_permissions](./0x01-shell_permissions/6-multiple_permissions)
- Description: Adds execute permission to the owner and group owner, and read permission to other users, to the file hello

### Task 7: Everybody!
- Script: [7-everybody](./0x01-shell_permissions/7-everybody)
- Description: Adds execution permission to the owner, the group owner, and other users, to the file hello

### Task 8: James Bond
- Script: [8-James_Bond](./0x01-shell_permissions/8-James_Bond)
- Description: Sets permission to the file hello with Owner: no permission, Group: no permission, Other users: all permissions

### Task 9: John Doe
- Script: [9-John_Doe](./0x01-shell_permissions/9-John_Doe)
- Description: Sets the mode of the file hello to `-rwxr-x-wx`

### Task 10: Look in the mirror
- Script: [10-mirror_permissions](./0x01-shell_permissions/10-mirror_permissions)
- Description: Sets the mode of the file hello the same as olleh’s mode

### Task 11: Directories
- Script: [11-directories_permissions](./0x01-shell_permissions/11-directories_permissions)
- Description: Adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users

### Task 12: More directories
- Script: [12-directory_permissions](./0x01-shell_permissions/12-directory_permissions)
- Description: Creates a directory called my_dir with permissions 751 in the working directory

### Task 13: Change group
- Script: [13-change_group](./0x01-shell_permissions/13-change_group)
- Description: Changes the group owner to school for the file hello

### Task 14: Owner and group
- Script: [100-change_owner_and_group](./0x01-shell_permissions/100-change_owner_and_group)
- Description: Changes the owner to vincent and the group owner to staff for all files and directories in the working directory

### Task 15: Symbolic links
- Script: [101-symbolic_link_permissions](./0x01-shell_permissions/101-symbolic_link_permissions)
- Description: Changes the owner and the group owner of _hello to vincent and staff respectively

### Task 16: If only
- Script: [102-if_only](./0x01-shell_permissions/102-if_only)
- Description: Changes the owner of the file hello to betty only if it is owned by the user guillaume

### Task 17: Star Wars
- Script: [103-Star_Wars](./0x01-shell_permissions/103-Star_Wars)
- Description: Plays the StarWars IV episode in the terminal

## Repository Information

- GitHub Repository: [alx-system_engineering-devops](https://github.com/alx-system_engineering-devops)
- Directory: 0x01-shell_permissions
