# DAY 2 :
* # Kernel and Shell
  
    ### Kernel:
    It is a program that is core of computer's operating system with complete control over everything in the system. It interacts with hardware.
    ### Shell:
    It is a program that acts an interface between user and operating system.
    
    ### Types of Shell:
    ### **_Bash_** :
    Most commmon (friendlist)
      
    A Command-Line Interpreter (Shell)
    Bash stands for Bourne Again SHell.
    It is the program you use to type commands in Linux or Mac. It lets you talk to the computer using text.

    💬 Think of it like:
    A messenger between you and the computer’s brain (kernel).
  
    You type a command like:
  
    **_cd Documents_**
  
    Bash takes it, understands it, and tells the computer what to do.


    ### **_Sh_** :
    Original shell (basic)
  
    ### **_Zsh_** :
    Fancy waiter, more features (managing file system)
  
    ### **_Fish_** :
    Modern interaction (files/programs)
     
    ## Categories:
    ---
    ### **_Commandline shell_**
  
   

    ### **_Graphical shell_**
  
   
* # Linux commands
    ### **_ls_** :
    Shows all files and folders in the current place in the form of a list.
      
    
  
    ### **_cd_** :
    Changes the directory (move into a folder).
      
   
  
    ### **_pwd_** :
    Prints working directory. Shows where you are right now.
      
    
    ### **_whoami_** :
    Who is using the computer. Tells the username.
      
   
    ### **_whatis_** :
    Gives short information about a command.

    ### ERROR : Shows nothing appropriate
  
      2 main reasons:
      Man (manual) database is not updated
      The command is unknown or not installed

   

    ### FIXING THE ERROR : Just update the whatis database using:
  
      sudo mandb
      This command builds the database so whatis can find info next time.

   

    ### ERROR RESOLVED :

   

    ### **_whereis_** :
    Tells where the command is. Finds where a program is installed.
      
   
    ### **_mkdir_** :
    Create a new directory (folder).
      
   
    ### **_rmdir_** :
    Deletes a directory, but only if it's empty.
      
   
  
    ### **_cat_** :
    It stands for concatenate. This is used to make file with content. various uses such as- file concatenation, to see the content of the file, copies the file content etc.
      
   
  
    ### **_touch_** :
    Creates an empty file. No content is written.
      
   
    ### **_nano_** :
    * A text editor in linux
    * Beginner-friendly
    * Simple and clear
      
    **_Commands shown at the bottom_**
      
        Ctrl + O → Save the file (O for Output)
        Ctrl + X → Exit
        Ctrl + K → Cut a line
        Ctrl + U → Paste
      
    ### **_vi_** :
    * It is also a text editor
    * The older, more powerful one
    * Comes pre-installed in all Linux systems
    * Harder for beginners

    ### __vi Modes__
    **_Command mode_** → You move around or delete/copy
  
    **_Insert mode_** → You can type and edit text

      Press i → to go into Insert mode (you can now type)
      Type your content
      Press Esc → to leave insert mode and go to command mode
      Type :w → to save (write)
      Type :q → to quit
      Type :wq → to save and quit
      Type :q! → to force quit without saving
  
    ### **_vim_** : Improved version of vi

      vim = "Vi IMproved"
      Better features, colors, undo/redo, etc.
      Still works with same modes (insert and command)

* # ASSIGNMENT
  ---
  
    ### **_cp_** :
    Makes a copy of a file or directory(folder). The original file or directory is not removed. We can copy one file into another file and also file into a folder known as directory.
      
 
  
    ### **_mv_** :
    Moves a file from one place to another. It removes the original file after moving to another file or directory.
      
  

 # sh shell
    sh is a basic shell (a command-line interpreter).
    It reads and runs commands, like echo, ls, cd, etc.
    You use it to run scripts written in a file.
    Think of sh like a robot that reads your .sh file line by line and does what you tell it to.

# .sh file
    A .sh file is just a text file full of Linux commands.
    It usually starts with this line:
    #!/bin/sh
  
    That line tells the computer:
    “Use the sh shell to run this file.”

**_What happens in the background_**

    Imagine sh is a person reading your .sh file:
    sh says: Okay, I see "echo Hello", I will say Hello.  
    


  

  

  

 
    
     
