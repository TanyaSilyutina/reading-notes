# List of Terminal Commands

#### Sources for the list: 
* [Linux Tutorial - 1. The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
* [Linux Tutorial - 2. Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)
* [Linux Tutorial - 3. More About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)
* Code Fellows 102 Class 2 "The Coders Computer"

### Definitions: 

1. GUI - graphical user interface
2. A command line, or terminal, is a text based interface to the system.
3. Shell - located within terminal. A part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. Bash is the most common. 
4. Absolute and Relative Paths - absolute paths specify a location in relation to the root directory; relative - specify a location in relation to where we are in the system 

### Terminal Commands:

* pwd - print working directory (shows what folder you're in)
* ls - lists contents in current directory
* ls -a – list all (shows hidden files and folders)
* mkdir ADDNAME – make directory (create a folder). Example: mkdir my-demo-folder
* cd – change directory. (go into another folder). Click TAB to loop thru existing folders
* touch – creates a new file (must specify file type), example: touch demofile.md
* cd .. – go back from directory (number of dots is how many levels you want to go back PLUS one extra dot); .. means go back once into previous folder
* tree – shows a file tree
* echo $SHELL - shows which shell you're using
* ls -l /etc - We ran ls with a command line argument ( /etc ). When we do this it tells ls not to list our current directory but instead to list that directories contents
* ~/(name) - a shortcut for home directory. if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
* ./(name) - reference to a directory within current directory, for example:

![image](https://user-images.githubusercontent.com/48433669/209428350-ee43ac6b-c5da-4493-9b50-6c0e5c92e985.png)





### More Examples: 
* Paths: 

![image](https://user-images.githubusercontent.com/48433669/209428160-135eb25e-fdee-4502-965c-2fb08a34d026.png)


* ~/(name)   ./(name) comparisons:

![image](https://user-images.githubusercontent.com/48433669/209428473-a1a6bdcb-97be-4831-a540-a854df9a67e7.png)


