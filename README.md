# LearnBase-Bash :book:
### Heared about Linux? Want to learn bash scripting? or Searching for a good Handbook for terminal Commands?

**HERE's ALL.**<br>
In a programmers' life, Linux is the thing that one should know how to use it efficiently.
This is a self learn tutorial for those who new to Linux terminal and want to learn how to use it effectively.

> This tutorial is covering the most used(80-90%) commands.

### 📙Let's Start❗

__1. ```man``` command__
 - to get the manual of commands that what specific command actually do and how to use it.
 - Syntax: ```man <command_name>```
 - use ```q``` key to exit from man page

__2. ```ls``` command__
 - list command, used to list the files.
 - Syntax: ```ls``` accepts a lot of options 
   - ```ls```
   - ```ls <folder_path>``` - to list files of a specific folder
   -  ```ls -al``` 
   
__3. ```mkdir``` command__
 - to create folders
 - Syntax:
   - ```mkdir <folder_name>``` - single folder
   - ```mkdir <folder1> <folder2>``` - multiple folders
   - ```mkdir -p <parentfolder / childfolder>``` - nested folders
   - 

__4. ```cd``` command__
 - cd means change directory. You can jump between folders using this command.
 -Syntax: 
   - ```cd <folder_name/path>```
   - ```cd ..``` - to back to parent folder
   - ```cd ../folder_name``` - 
   - ```cd /<foldername>``` - use absolute paths, which start from the root folder ```/```

__5. ```pwd``` command__
 - prints current folder path.
 
__6. ```rmdir``` command__
 - delete __empty__ folders using this command
 - Syntax:
   - ```rmdir <folder_name>
   - ```rm -rf <folder>``` : _To delete folders with files in them_
   > ❗ NOTE: this command does not ask for the confirmation from the user and immediately remove that you ask it to remove.

__7. ```touch``` command__
 - to create an empty file
 - Syntax: ```touch <file_name>
 - If the file already exists, it opens th file in write mode.

__8. ```mv``` command__
 - to move the file and also to rename the file
 - ```mv <from_folder/file> <to_folder/file>``` 
 - ```mv <file1> <file2> <tofolder>``` - to move more than one file, make a list of file and move to folder.

__9. ```cp``` command__
 - to copy a file

__10. ```open``` command__
 - to open a file using this command
 - Syntax: ```open <filename>```
  
__11. ```find``` command
 - used to find files or folders matching a particular search pattern. It searches recursively.
 - Example: to find all the files in current directory with extension ```.png``` and also print the relative path. 
  - ```find . -name '*.png'``` 
