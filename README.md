# LearnBase-Linux Terminal Commands(LTC) :book:
### Heared about Linux? or Searching for a good Handbook for terminal Commands?
> 🏗️**This Repository still under construction. But feel free to explore and contribute** 🤿

**HERE's ALL.**<br>
In a programmers' life, Linux is the thing that one should know how to use it efficiently.
This is a self learn tutorial for those who new to Linux terminal and want to learn how to use it effectively.

> This tutorial is covering the most used(80-90%) commands.<br>

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
   - ```rmdir <folder_name>```
   - ```rm -rf <folder>``` : _To delete folders with files in them_
   > ❗ NOTE: this command does not ask for the confirmation from the user and immediately remove that you ask it to remove.


__7. ```touch``` command__
 - to create an empty file
 - Syntax: ```touch <file_name>```
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
  
  
__11. ```find``` command__
 - used to find files or folders matching a particular search pattern. It searches recursively.
 - ```file . -name <file_name>``` - to find the file with its name.
 - Example: to find all the files in current directory with extension ```.png``` and also print the relative path. 
   - Syntax:
   - ```find . -name '*.png'```
   - 


__12. ```gzip``` command__
 - to compress a file with extension ``` .gz```
 - Syntax: 
   - ```gzip <file_name>``` : using this the original file will be deleted.
   - ```gzip -c <file_name> > <filename.gz>``` : using ```-c``` option specifies that the output will go to the standard output stream without affecting original file.
   
   > or can use -k option 
   
   ```gzip -k <file_name>```
   - ```gzip <file1> <file2>``` : to zip mutiple files
   - 🟡```gzip -r <folder_name>```: to compress a folder recursively
   - 🟢```gzip -d <file_name.gz>``` : to decompress a file


__13. ```gunzip``` command__
 - equivalent to ```gzip``` command, but ``` -d``` option is enabled by default.
 - Syntax: 
  - ```gunzip [option] [archive name/file name]```


__14. ```alias``` command__
 - to create your command for your convenience.
 - Example: 
   - ```alias ll = 'ls -al'``` : use ```ll``` in place of ```ls -al``` command
 - ```alias``` : *(with no option)* to list all alias defines


__15. ```cat``` command__
 - *SUPER POWERFUL command*
 - ```cat <file_name>``` : prints a file content
 - ```cat <file1> <file2>``` : to print multiple file content
 - ```cat <file1> <file2> > file3``` : to concatenate the content of multiple files into a new one.
 - ```cat <file1> <file2> >> <file3>``` : to append content of multiple files into new one.
 - ```cat <file_name> | <another_command>``` : to feed a file's content as input to another command.
 - ```cat -s <file_name>``` to remove multiple empty lines.


__16. ```less``` command__
 - to watch the file content in an interactive UI
 - ```less <filename>```


__17. ```head``` and ```tail``` command__
 - ```head``` to print first 10 lines of the file.
 - ```tail``` to print last 10 lines of the file.


__18. ```wc``` command__
 - helps in counting the lines, words, and characters in a file. Mostly, it is used with pipes ```|``` for counting operation.
 - It will display the number of lines, words, and bytes from the file.
 - Syntax: ```wc [option]... [file]...```


__19. ```grep``` command__
 > grep command filters the content of a file which makes search easy.
 > _grep_ stands for global regular expression print.
 
 - _helpful in day-to-day coding_
 - Syntax: 
   - ```command | grep <searchWord>``` : with pipes (case sensitive by default)
   - ```grep <search_Word> <file_name>``` : without pipes
   - ```grep -v <search_Word> <file_name>``` : to search for non-matching searched word.
   - ```grep -i <searchWord> <filename>``` : to filter output in a case-insensitive way.


__20. ```sort``` command__
 - used to sort the list items
 - ```sort <file_name>``` : by default case sensitive and alphabetic.
 - ```sort -r <file_name>``` : reverse order sort.
 -  ```sort --ignore-case <file_name>``` : to sort case insensitive, use ```-n``` to sort numerically.
 -  ```sort -u <file_name>``` : to remove duplicated.
 -  Example : ```ls | sort``` : used with list command.

 
