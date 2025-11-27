0x02. Shell, I/O Redirections and Filters
Description
This project focuses on understanding and implementing shell I/O redirections, filters, and special characters in Bash scripting. The tasks involve manipulating standard input/output, working with files, and using various command-line utilities to process and redirect data.

Learning Objectives
By completing this project, you will understand:

What do the commands head, tail, find, wc, sort, uniq, grep, tr do
How to redirect standard output to a file
How to get standard input from a file instead of the keyboard
How to send the output from one program to the input of another program
How to combine commands and filters with redirections
What are special characters and how to use them
How to display a line of text
What is the shell and what is the difference between a terminal and a shell
Requirements
Allowed editors: vi, vim, emacs
All scripts will be tested on Ubuntu 20.04 LTS
All scripts should be exactly two lines long (wc -l file should print 2)
All files should end with a new line
The first line of all files should be exactly #!/bin/bash
All files must be executable
You are not allowed to use backticks, &&, || or ;
All scripts must work without running them with bash command
Project Structure
0x02-shell_redirections/
├── README.md
├── 0-hello_world
├── 1-confused_smiley
├── 2-hellofile
├── 3-twofiles
├── 4-lastlines
├── 5-firstlines
├── 6-third_line
├── 7-file
├── 8-cwd_state
├── 9-duplicate_last_line
└── 10-no_more_js
Tasks
0. Hello World
File: 0-hello_world
Write a script that prints "Hello, World", followed by a new line to the standard output.

Usage:

bash
./0-hello_world
1. Confused Smiley
File: 1-confused_smiley
Write a script that displays a confused smiley "(Ôo)'.

Usage:

bash
./1-confused_smiley
2. Let's Display a File
File: 2-hellofile
Display the content of the /etc/passwd file.

Usage:

bash
./2-hellofile
3. What About 2?
File: 3-twofiles
Display the content of /etc/passwd and /etc/hosts.

Usage:

bash
./3-twofiles
4. Last Lines of a File
File: 4-lastlines
Display the last 10 lines of /etc/passwd.

Usage:

bash
./4-lastlines
Hint: Think of it as a cat, what is at the end of it?

5. I'd Prefer the First Ones Actually
File: 5-firstlines
Display the first 10 lines of /etc/passwd.

Usage:

bash
./5-firstlines
6. Line #2
File: 6-third_line
Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory
You're not allowed to use sed
Usage:

bash
./6-third_line
7. It Is a Good File That Cuts Iron Without Making Noise
File: 7-file
Write a shell script that creates a file named exactly \*\\'Best School'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

Usage:

bash
./7-file
8. Save Current State of Directory
File: 8-cwd_state
Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Usage:

bash
./8-cwd_state
9. Duplicate Last Line
File: 9-duplicate_last_line
Write a script that duplicates the last line of the file iacta.

The file iacta will be in the working directory
Usage:

bash
./9-duplicate_last_line
10. No More JavaScript
File: 10-no_more_js
Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

Usage:

bash
./10-no_more_js
Key Concepts
I/O Redirection Operators
> - Redirect output to a file (overwrite)
>> - Redirect output to a file (append)
< - Redirect input from a file
| - Pipe output from one command to another
Common Commands Used
echo - Display a line of text
cat - Concatenate and display file contents
head - Output the first part of files
tail - Output the last part of files
find - Search for files in a directory hierarchy
wc - Print newline, word, and byte counts
sort - Sort lines of text files
uniq - Report or omit repeated lines
grep - Print lines matching a pattern
tr - Translate or delete characters
Special Characters
\ - Escape character
* - Wildcard (matches any characters)
? - Wildcard (matches single character)
$ - Variable prefix
' - Single quote (literal string)
" - Double quote (allows variable expansion)
Resources
Shell I/O Redirection
Special Characters in Bash
Linux man pages: man bash, man cat, man head, man tail, man find
Repository Information
GitHub repository: system_engineering-devops
Directory: 0x02-shell_redirections
Author
This project is part of the System Engineering & DevOps curriculum.

Note: All scripts must be executable. Use chmod +x filename to make a script executable before testing.


