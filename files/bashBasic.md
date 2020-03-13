### Bash basic command 
- file: linux does not need the extension to function, file command could be used to tell the file type. 
- locate: help to file the file in the system base on a file management database.
- which: find other command in the system and the location of where it gets installed.
- cal: little command show the date for today.
- history: command history
- apropos: want to search for a command that has something vague task.
- whatis, man: short and long explaination of a specific command.
- mv: could be used to move around the file system or used to rename the file or mv the content of the file into another file.
- cp: cp file then paste to another location. 
- cat: show the content in file, cat >> file, input file content to file, hit control-d to finish typing the content.
    cat >> file (append infomation), cat > file (replace the old info with new input info)
- cat file1 cat file2: concatenate file1 and file2 together and prompt on the screen. (more and less, less is a more useful one.)
- sudo -s: change into the sudo user. 
- file permission: Owner Group sizeOfTheFile nameOfTheFile
    r: read     w: write    x: execute
    ownerPermission-groupPersmission-everybodyElse
    d:represents directory      -: represents file
    drwx------@  3 lee  staff    96 Nov 29 12:08 Applications
    drwx------@ 15 lee  staff   480 Feb 29 16:16 Desktop
    drwx------@  8 lee  staff   256 Feb 20 14:48 Documents
    drwx------@  9 lee  staff   288 Feb 27 09:05 Downloads
    drwx------@ 22 lee  staff   704 Feb 15 20:50 Dropbox
- chmod: change the permission of the above file and directory. (seven bit: 4-2-1)
