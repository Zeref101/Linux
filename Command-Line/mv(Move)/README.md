## mv(Move)
Used for moving files and also renaming them. Quite similar to the cp command in terms of flags and functionality. 
* You can rename files like this:
```shell
$ mv oldfile newfile
```
* Or you can actually move a file to a different directory: 
```shell
$ mv file2 /home/pete/Documents
```
* And move more than one file:
```shell
$ mv file_1 file_2 /somedirectory
```
* You can rename directories as well:
```shell
$ mv directory1 directory2
```
## Like cp, if you mv a file or directory it will overwrite anything in the same directory. So you can use the -i flag to prompt you before overwriting anything.
```shell
mv -i directory1 directory2
```