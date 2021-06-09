# Working with Scripts and their outputs
### Meaning of the above scrips


0. 0-current_working_directory 
   > excutable file created in 0-current_working_directory

1. listit 
   > Displays the contents list of your current directory.

2. bring_me_home  
   >  a script that changes the working directory to the user’s home directory
3. listfiles  
   > it displays current directory contents in a long format
4. listmorefiles
   > it display current directory contents, including hidden files (starting with .). Use the long format.
5. listfilesdigitonly
   > Display current directory contents.
   > * Long format
   > * with user and group IDs displayed numerically
   > * And hidden files (starting with .)
6. firstdirectory
   > it Create a script that creates a directory named holberton in the /tmp/ directory.
7. movethatfile
   > it moves files in our case we move the file `betty` from `/tmp/`to `/tmp/holbertonty`
8. firstdelete
   > it delets the file `betty`
9. firstdirdeletion
    > Delete the directory `holberton` that is in the `/tmp directory`
10. back
    >this script changes the working directory to the previous one.
11. lists
    > a script that lists all files (even ones with names beginning with a period character, which are normally `hidden`) in the current directory and the parent of the working directory and the `/boot` directory (in our case), in long format. 
12. file_type
    > a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp `directory when we will run your script.
13. symblic_link
    > `symbolic` link (also symlink or soft link) is a term for any file that contains a reference to another file or directory in the form of an absolute or relative path and that affects pathname resolution.

    > a `symbolic` link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.
14. copy_html
    > this create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

### bonuses 

100. lets_move
     > it create a script that moves all files beginning with an `uppercase `letter to the directory `/tmp/u.` 
101. clean_emacs
     > it create a script that deletes all files in the current working directory that end with the character `~`.
102. tree
     > it create a script that creates the directories `welcome/`, `welcome/to/ `and `welcome/to/holberton` in the current directory. 
   
     > only with simple line
103. commas


     > a command that lists all the files and directories of the current directory, separated by commas `(,)`.

     >> *  Directory names should end with a slash (/)

     > >* Files and directories starting with a dot (.) should be listed

     > >* The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning 

     > >*  Only digits and letters are used to sort; Digits should come first
     > >*  You can assume that all the files we will test with will have at least one letter or one digit
     > >*  The listing should end with a new line
   ****