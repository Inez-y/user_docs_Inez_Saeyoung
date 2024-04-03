# How to delete a File with Command Line on the Terminal

## Overview

This section will cover how to delete files and directories in your computer through the terminal.

## Before start

Be careful. Deletion through the command line is permanent. Deleted files can not be restored.

### Step 1: Check where is your current location `pwd`

Confirming your current location in the terminal is an always good start. You can check your location by typing command line `pwd` in your terminal screen. The terminal will show you similar result with below.

```
/Users/[PC_main_directory]
```

### Step 2: See the list of files or directories in the current level `ls`

Check what you have in the current level by typing command line `ls` in your terminal screen. The terminal will show you similar result with below.

```
Applications		      OneDrive
CLionProjects		      Pictures
Creative Cloud Files	  Public
Desktop			          PycharmProjects
Documents		          ScreenPal
Downloads		          VSCodeProjects
Library	                  test_file.txt
Movies                    Music
```

### Step 3: Delete the file with `rm`

`rm` stands for remove. After `rm` command line you can put file name including extension or absolute path.

```
rm test_file.txt
```

### Step 4: Delete the folder with `rmdir`

`rmdir` stands for remove directory.

```
rmdir test_folder
```

## Confirm the deletion

You can check whether the deletion is executed or not via terminal or via Graphic User Interface(GUI) at your computer.

1. Type `ls` at the parent directory.
2. Go to the directory at your computer screen through Finder.

## Conclusion

Now you can navigate, create, delete a file or directory on your computer through the command line on the terminal! :partying_face:
