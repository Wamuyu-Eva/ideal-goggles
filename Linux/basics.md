## Some Basic Linux Commands - What I consider basic :)

### man Command
Displays the user manual of commands that one can run on the terminal. 

#### Usage of this command
``` man [option] [command] ```

    man [name-of-the-command]
    Explains more on the usage of the command. 
    The explanation includes the name, synposis, description, author, copyright

    man [with options]
    man -k [keyword]: Search for manual pages that contain that key word.
    man -f [name-of-the-command]: Display one line description of the command
    man -h / man --help: Display a help message with information on how to use the man command.

### pwd
(Print Working Directory) displays the current working directory's full name.

#### Usage of Pwd
``` pwd [option]```

    pwd -L, --logical: Gives the logical path
    pwd -P, --physical: Provides the physical path - shows the actual path without following symbolic links.
    pwd --help: shows how to use the pwd command.
    

### whoami
Print effective userid

#### Usage of whoami
``` whoami [option]```

    whoami -L, --logical: Gives the logical path
    whoami --help: shows how to use the pwd command.
    whoami -version

### cd
Change Directory

#### Usage of cd

    cd (without arguments)/cd ~: Changes the directory to the user's home directory.
    cd [with directory path]: Changes the path to the directory path or shows (No such file or directory if the path is invalid)
    cd .. : Changes the path one level in the directory.
   

### mkdir
(Make Directory) Command used to create directories. 

#### Usage of mkdir
``` mkdir [options] directory_name```
``` mkdir [options] ```

    mkdir -p [filepath/filename]: Allows creating parent directories. If the directories exists, no error is thrown.
    mkdir --help: Offer help on usage of the command.
    mkdir -m=[set permisions] [filename]: Create directory and define permissions. 

### clear
Clears the terminal screen


### touch
Create files which are blank or empty
``` touch [filename]```

### ls
List directories
``` ls ```
``` ls [directory-to-list-content]```

### cp
Copy files and directories from one location to another
``` cp [options] source destination ```

    cp -r [source] [destination] : Copy directories recursively. Necessary when copying directories and their contents.
    
    


    
 

    
    


   