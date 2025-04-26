# Linux Basics 101

The information found within this file are some of the more common commands that anybody working within Ubuntu will use from the terminal. Its worth putting some effort into learning the commands but also learning exactly what they do.  This has helped me enormously on my linux journey and I hope it will for you to.  Make sure to practice regularly and type commands building knowledge, experience, and **muscle memory**.  My hope is that anybody from a kid to their parents, teachers, uncle who is a hobbyist, to seasons admins will find benefit in these collections of files.

## Let's Get Started!

1. The first step to take is to open a terminal whether that is a terminal window on Ubuntu Desktop or Server, or a Windows Gitbash terminal.  It is within the terminal that we will be spending our time providing commands to the system.
2. What is the terminal? I think it is best described as a direct channel for you to talk to the system and issue commands to complete the tasks you need it to perform.  
3. What types of commands can you provide to the terminal? The list is quite long really it is, but it all starts with some foundational commands on which you can then build out in the future for more complex tasks.  For example you can provide commands to:
    - Create, edit, remove files and directories.
    - Download and install applications.
    - Update and upgrade applications, and core package files.
    - Manage system processes and resources.
    - Write scripts to automate tasks.
    - and much more...
4. The best way to learn anything is by getting your hands dirty, so open a terminal and let's get going.

## Navigating You System in the Terminal

- **If you want to**: know the current working directory. **Type**: `pwd` in the terminal. **Meaning**: *print the working directory*. **Example**: typing `pwd` outputs */home/alex* is the directory you are currently in.
- **If you want to**: see what is inside a directory. **Type**:

| **If you want to...**                      | **Type**            | **What is means**               | **Example**      |
| -------------------------------------------| ------------------- | --------------------------------| ---------------- |
| know the current working directory         | `pwd`               | *print the working directory*   | `/home/alex`     |
| see what's inside a directory              | `ls`                | *list items in directory*       | `ls /etc`        |
| change into another directory              | `cd <directory>`    | *change directory*              | `cd Documents`   |
| move one step up the directory hierarchy   | `cd ..`             | *.. is the parent directory*    | `cd ..`          |
| return home instantly                      | `cd` (nothing else) | *return to your home directory* | `cd`             |

**TIP**: *Tab-key autocompletes names. Hit it twice to see choices*.

-------------------------------------------------------------------------------------------------------------------------------------------

## Take A Look Inside

| **Goal**                   | **Command**      | **Quick Note**               |
| -------------------------- | ---------------- | ---------------------------- |
| Show text on screen        | `cat file.txt`   | Good for small files         |
| Scroll through long text   | `less file.txt`  | Up/Down arrows to move       |
| Only first few lines       | `head file.txt`  | Default 10 lines; add -n 5   |
| Only last few lines        | `tail file.txt`  | Add -f to watch a live log   |

## Making, Copying, Moving, Deleting

| **Action**                 | **Command           | **Example**                  |
| -------------------------- | ------------------- | ---------------------------- |
| Create an empty file	     | `touch story.txt`   | `touch mylist.txt`           |
| Make a new folder	         | `mkdir Pictures`	   | `mkdir project2025`          |
| Copy files	             | `cp old.txt new.txt`| `cp photo.jpg backup/`       |
| Copy folders         	     | `cp -r old/ new/`   | `-r = recursive`             |
| Move or rename	         | `mv old.txt new.txt`| `mv draft/ final/`           |
| Delete file            	 | `rm file.txt`       | `Careful: no recycle bin!`   |
| Delete empty folder	     | `rmdir folder`	   | `Must be empty`              |
| Delete folder + contents	 | `rm -r folder`	   | `Think twice, then type`     |

**Safety net**: add -i to ask “Are you sure?”
**Example**: rm -i important.doc






