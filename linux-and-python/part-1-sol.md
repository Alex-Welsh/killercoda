### Part 1 - The Linux terminal - Solutions!

- How many files are there in this directory?
    - There are _probably_ 5 files. A surprisingly tricky question because
      there are hidden files in this directory. There is one visible file,
      which you can see if you use a standard `ls`{{exec}} command
      (`rock-paper-scissors.py`) and four more if you list all files with `ls
      -a`{{exec}} - `.bash_history`, `.bashrc`, `.profile`, and `.vimrc`. And
      there's always a chance that you could have created or deleted files
      so... it depends!
- What are the contents of the `rock-paper-scissors.py` file in this directory?
    - the file contains (the start of) a little python program, but it's far
      from complete. There are lots of commands to peek inside files but some
      examples include `cat`, `less`, and `vim`.
- What is the name of the directory you are in?
    - The working directory is `/root` which can be found with `pwd`{{exec}}.
      If you want to be really fancy, you can try `realpath .`{{exec}} which
      will also resolve any symlinks, and give you the _true_ file path.


<br>

## Extension questions - Solutions!

- What Operating System is the lab node running?
    - Ubuntu 20.04 (Focal Fossa). As always there are a few ways of checking
      this, one way would be to look in the `/etc/os-release` file. 
- How much system memory is available to you?
    - One way to check system memory is the `free`{{exec}} command, which will
      give you the the exact amount of memory in kilobytes. For a more readable
      output, try `free -h`{{exec}} which will normalise the units. Both
      commands will tell you there's 2GB of memory.
- What is the current date?
    - It depends! Okay, that may be obvious, and of course you can just check your phone. If you don't want to leave your nice cosy Linux terminal, just use the `date`{{exec}} command.
