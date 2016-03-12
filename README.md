# WYshell
EECE7376 Operating System -- Midterm Project
Team members: Wuji Situ, Yong Yu
==========================================
Please complie this project with command: gcc WYshell.c command.c -o <filename>

Features:
1. WYshell will print a Prompt when is ready for user command input, the format of the Prompt is <Username>@WYshell : <current working directory> .
2. Commands can running in foreground or background. When running in the background, the pid of the last sub-command will be printed. WYshell will also print a message whenever a process finishes that launched in the background. 
3. Proper error messages will be printed when user input wrong commands.
4. Redirect operators are supported.
5. Pipe between sub-commands are supported.
6. The "cd" built-in command is implemented.

