## ls(List Directory)
The ls command will list directories and files in the current directory by default, however you can specify which path you want to list the directories of.
```shell
$ ls /home/shreyas
```
```
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos
```
* Not all files in a directory will be visible. Filenames that start with . are hidden, you can view them however with the ls command and pass the -a flag to it (a for all).
```shell
$ ls -a
```
```
              .bashrc    .dotnet     .mozilla             Public     .vscode
..             .cache     Downloads   Music                Templates
.bash_history  .config    .gitconfig  .nvidia-settings-rc  .themes
.bash_logout   Desktop    .lesshst    Pictures             .var
.bash_profile  Documents  .local      .pki                 Videos
```
* -l for long, this shows a detailed list of files in a long format. This will show you detailed information, starting from the left: file permissions, number of links, owner name, owner group, file size, timestamp of last modification, and file/directory name. 
```shell
$ ls -l
```
```
drwxr-xr-x. 1 shreyas shreyas   0 Apr 13 10:09 Desktop
drwxr-xr-x. 1 shreyas shreyas 120 Apr 18 10:25 Documents
drwxr-xr-x. 1 shreyas shreyas 354 Apr 16 10:43 Downloads
drwxr-xr-x. 1 shreyas shreyas   0 Apr 13 10:09 Music
drwxr-xr-x. 1 shreyas shreyas   0 Apr 13 10:09 Pictures
drwxr-xr-x. 1 shreyas shreyas   0 Apr 13 10:09 Public
drwxr-xr-x. 1 shreyas shreyas   0 Apr 13 10:09 Templates
drwxr-xr-x. 1 shreyas shreyas   0 Apr 13 10:09 Videos
```
* Commands have things called flags (or arguments or options, whatever you want to call it) to add more functionality. We added -a and -l, well you can add them both together with -la. 
```shell
$ ls -la
```
Some more ls flag
* ls -R: recursively list directory contents
* ls -r: reverse order while sorting
* ls -t: sort by modification time, newest first