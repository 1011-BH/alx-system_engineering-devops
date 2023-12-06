# Shell Basics - ALX DevOps Project

This repository contains a series of shell scripting tasks aimed at familiarizing individuals with basic Unix/Linux commands, file operations, and scripting in the Bash shell.

## Project Overview

The tasks cover various aspects of shell scripting and file manipulation, focusing on topics such as navigation, file listing, directory operations, and more.

### Tasks Included

Each task is encapsulated in a separate script file within the `0x00-shell_basics` directory. Below is a list of tasks included in this project along with their respective answers:

0. **Where am I?**
   - Script: [0-current_working_directory](./0-current_working_directory)
   - Description: Prints the absolute path name of the current working directory.

1. **What’s in there?**
   - Script: [1-listit](./1-listit)
   - Description: Displays the contents list of the current directory.

2. **There is no place like home**
   - Script: [2-bring_me_home](./2-bring_me_home)
   - Description: Changes the working directory to the user’s home directory.

3. **The long format**
   - Script: [3-listfiles](./3-listfiles)
   - Description: Displays the current directory contents in a long format.

4. **Hidden files**
   - Script: [4-listmorefiles](./4-listmorefiles)
   - Description: Displays current directory contents, including hidden files, using the long format.

5. **I love numbers**
   - Script: [5-listfilesdigitonly](./5-listfilesdigitonly)
   - Description: Displays current directory contents in long format with user and group IDs displayed numerically, including hidden files.

6. **Welcome**
   - Script: [6-firstdirectory](./6-firstdirectory)
   - Description: Creates a directory named my_first_directory in the /tmp/ directory.

7. **Betty in my first directory**
   - Script: [7-movethatfile](./7-movethatfile)
   - Description: Moves the file betty from /tmp/ to /tmp/my_first_directory.

8. **Bye bye Betty**
   - Script: [8-firstdelete](./8-firstdelete)
   - Description: Deletes the file betty from /tmp/my_first_directory.

9. **Bye bye My first directory**
   - Script: [9-firstdirdeletion](./9-firstdirdeletion)
   - Description: Deletes the directory my_first_directory from the /tmp directory.

10. **Back to the future**
    - Script: [10-back](./10-back)
    - Description: Changes the working directory to the previous one.

11. **Lists**
    - Script: [11-lists](./11-lists)
    - Description: Lists files in the current directory, parent of the working directory, and the /boot directory in long format.

12. **File type**
    - Script: [12-file_type](./12-file_type)
    - Description: Prints the type of the file named iamafile in the /tmp directory.

13. **We are symbols, and inhabit symbols**
    - Script: [13-symbolic_link](./13-symbolic_link)
    - Description: Creates a symbolic link to /bin/ls named __ls__ in the current working directory.

14. **Copy HTML files**
    - Script: [14-copy_html](./14-copy_html)
    - Description: Copies HTML files from the current working directory to the parent of the working directory.

15. **Let’s move**
    - Script: [100-lets_move](./100-lets_move)
    - Description: Moves all files beginning with an uppercase letter to the directory /tmp/u.

16. **Clean Emacs**
    - Script: [101-clean_emacs](./101-clean_emacs)
    - Description: Deletes all files in the current working directory that end with the character ~.

17. **Tree**
    - Script: [102-tree](./102-tree)
    - Description: Creates the directories welcome/, welcome/to/, and welcome/to/school in the current directory.

18. **Life is a series of commas, not periods**
    - Script: [103-commas](./103-commas)
    - Description: Lists all the files and directories of the current directory, separated by commas.

19. **File type: School**
    - Script: [school.mgc](./school.mgc)
    - Description: Creates a magic file that can be used with the command file to detect School data files.

## Running the Scripts

### Setting Execution Permissions

Before running the scripts, ensure they have execution permissions. You can use the `chmod` command to grant execution permissions.

Open your terminal, navigate to the directory containing the scripts, and execute the following command to grant execution permissions to a script:

```bash
chmod +x <script_name>

