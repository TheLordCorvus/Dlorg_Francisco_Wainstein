# Dlorg_Francisco_Wainstein
Working with Dlorg Lab

## First Line from inside VM Dlorg directory
This is my first message to test it works, and with this, the first official commit.

## gitignore file

A file was created called vim.gitignore to ignore vim related stuff when committing to the repository

# Bash script

Created a bash script file called dlorg.
checked and gave new permissions to file using ls -l and chmod

```bash

ls -l dlorg

chmod +x dlorg

```
# Dlorg script

The script created has the purpose of creating (if not already created) folders for specific type of files, and then check existing files inside the directory if they has one of the suffixes listed in the script. If they do, then they are moved to their respective folders for better file management.

For the script to work one needs atleast a second terminal to use the following command;
```
./dlorg
```
Inside the repository directory, and the other terminal in the Downloads directory. So first you create the files using touch, and after they are created, execute the command.


# Dlorg Update script

Created a second script to watch the first, and execute it when a new file is added to the Downloads directory in home.

While the script is being executed, any and all files that comes into the Downloads directory gets sorted.

For example using mv to move an image file from home to Downloads and it went straight to the Images folder.

![Downloads Tree](Dlorg_Francisco_Wainstein)


