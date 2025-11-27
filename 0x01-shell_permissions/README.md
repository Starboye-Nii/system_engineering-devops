This directory contains scripts that demonstrate basic Linux permission commands.
Each script performs one specific task and must be executable before running.

📌 How to Run the Scripts

Open your terminal

Go into this project folder:

cd 0x01-shell_permissions


Make the script executable (only needed the first time):

chmod +x filename


Run the script:

./filename

📜 Script Descriptions
File	Description
0-iam_betty	Switches the current user to the user betty.
1-who_am_i	Prints the effective username of the current user.
2-groups	Prints all the groups the current user is part of.
3-new_owner	Changes the owner of the file hello to the user betty.
4-empty	Creates an empty file called hello.
5-execute	Adds execute permission to the owner of the file hello.
6-multiple_permissions	Adds execute permission to the owner and group owner, and read permission to others for the file hello.
7-everybody	Adds execute permission to owner, group, and others for the file hello.
8-James_Bond	Sets permissions of hello so that only others have all permissions.
9-John_Doe	Sets the file hello to specific permissions: -rwxr-x-wx.
10-mirror_permissions	Mirrors the permissions of hello to olleh.
11-directories_permissions	Adds execute permission to all subdirectories of the current directory for all users.
12-directory_permissions	Creates a directory called my_dir with permissions 751.
13-change_group	Changes the group owner of the file hello to school.
📝 Notes

All scripts start with:

#!/bin/bash


No script should contain semicolons (;), backticks, or logical operators (&&, ||).

Scripts must work in a clean Ubuntu environment as used by ALX checkers.
