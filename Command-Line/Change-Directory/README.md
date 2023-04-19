##  cd (Change Directory)
There are two different ways to specify a path, with absolute and relative paths. 
* Absolute path: This is the path from the root directory. The root is the head honcho. The root directory is commonly shown as a slash. Every time your path starts with / it means you are starting from the root directory. For example, /home/pete/Desktop.
* Relative path: This is the path from where you are currently in filesystem. If I was in location /home/pete/Documents and wanted to get to a directory inside Documents called taxes, I don’t have to specify the whole path from root like /home/pete/Documents/taxes, I can just go to taxes/ instead.
```shell
$ cd /home/shreyas/Downloads
```
Shortcuts
* . (current directory). This is the directory you are currently in.
* .. (parent directory). Takes you to the directory above your current.
* ~ (home directory). This directory defaults to your “home directory”. Such as /home/pete.
* '-' (previous directory). This will take you to the previous directory you were just at.

### Running the "cd" command without any flags in the terminal takes you to the home directory of the current user.