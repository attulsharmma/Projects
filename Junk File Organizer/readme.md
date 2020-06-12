# Junk File Organizer with Python
Basically, as a lazy programmer my desktop is full of files (Junk Files). Due to the large number of files, it is a daunting task to sit and organize each file. To make that task easy the below Python script comes handy and all the files are organized in a well-manner within seconds.

__Main functionality of this code__

1. Organize by extension
2. Organize by size 
3. Organize by last used date
4. Reset


## 1. Organize by extension
---
by using this option user can organize their files by their file extension in a given folder, folder will be created according to file type/extension and finally all folder will be moved to a given folder (default is Organized), user can edit folder name

## 2. Organize by size
---
by using this option user can organize their files by their file size, according to file sizes random folders will be created and respective files will be moved to them, and finally all folder will be moved to a given folder (default is Organized), user can edit folder name

## 3. Organize by Last used/accessed date
--- 
by using this option user can organize their files by last used date. random folders will be created according to file's last used date and files will be moved to them and finally all folder will be moved to a given folder (default is Organized), user can edit folder name

## 4. Reset
 This is basically a helper function for this whole code. what happens is when we organize some files with extension or size with this project all file will be in their respective folders inside main folder, but if we want to test another operation like organize files with last used date then we have to move each files from organized folder to their original folder( Initial path of all files) but this option makes same work easy. (see demo)
