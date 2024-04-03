# How to delete a File with Command Line on the Terminal

## Overview

This section will cover how to delete a file and folder in your computer through the terminal.

!! warning

    Be careful. Deletion through the command line is permanent. Deleted files can not be restored.

## Delete

1. Check where is your current location `pwd`

   Confirming your current location in the terminal is an always good start. You can check your location by typing command line `pwd` in your terminal screen. The terminal will show you similar result with below.

   ```
   /Users/[PC_main_folder]
   ```

2. See the list of files or folders in the current level `ls`

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

3. Delete the file with `rm`

   `rm` stands for remove in this command. After `rm` command line you can put file name including extension or absolute path.

   ```
   rm test_file.txt
   ```

4. Delete the folder with `rmdir`

   `rmdir` stands for remove folder in this command.

   ```
   rmdir test_folder
   ```

5. Confirm the deletion

   You can check whether the deletion is executed or not via terminal or via Graphic User Interface(GUI) at your computer.

   - Type `ls` at the parent folder which means higher hierarchy.
   - Go to the folder at your computer screen through Finder.

## Conclusion

Now you can navigate, create, and delete a file or folder on your computer through the command line on the terminal! :partying_face: This is very basic jobs you can do through the command line. You can explore further on [Apple macOS command line](https://ss64.com/mac/)
