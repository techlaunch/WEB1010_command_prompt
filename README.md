# WEB1010_command_prompt
Quick guide on how to use the command prompt

## How the command prompt works
The "prompt" is a blinking vertical line at the end of your terminal. When the line blinks, means is ready to receive a command. When you hit a command and press Enter, the computer will receive it, process it, return a response and give the "prompt" back to you.

## The file system is a tree
![the file system](https://www.ntu.edu.sg/home/ehchua/programming/howto/images/DirectoryStructure.png)

## Navigate though the file system
```
pwd: check the path where you are located  
ls -lah: display the content of the current directory  
cd: followed by a path to open a directory  
cd ..: opens the parent directory  
tab key: use the tab key to autocomplete a path or file name  
.file: hidden files start with a "."  
```

## Absolute v.s. Relative paths
You can always start by the root (absolute) or from the current location (relative) when trying to access a file or directory on the file system.

## Create new files and directories
```
touch: create a new file  
mkdir: create an empty directory  
cat: display the content of a file  
less: display the content of a file paginated  
tail: display the last 10 lines of a file  
nano: edit a file  
```

## Work with files and directories
```
cp: copy a file or directory  
mv: move or rename a file or directory  
rm -rfv: deletes a file or directory. BE CAREFUL!  
```

## Other important commands
```
df -h: check the space in the HD  
clear: cleans the console  
>: redirect command results to a file  
|: redirect command results to another command (pipes)  
```
