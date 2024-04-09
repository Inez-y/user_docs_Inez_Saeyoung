# How to navigate files and folders with Command Line

## Overview

Our goal of this section is navigate to the Documents folder of your computer and open the folder. To do that, first, we will check your current located folder. Second, we will print the list of files and folders in the specific folder on the Terminal. Then, we will learn how to write the folder path in two different ways: Absolute path, and relative path. Finally, we will navigate to the destination folder, and open the folder.

### Navigate to a file and folder

1. Click the Terminal icon, and open the Terminal.

2. Type `pwd` in your terminal window to see where is your current location.

    `pwd` represents "print working directory" in this command. With this command you can see absolute path of your current located folder which means your location from the root folder of your computer. The result of `pwd` will be printed in the Terminal similar with this expression: `/Users/[user_name]` or `/Users/[user_name]/Documents/term2`


3. Type `ls` to see what folders and files in your current located folder.

    The result of `ls` will be printed in the Terminal similar with below.

    ```
    Applications		 	   test_file.txt
    Desktop			           Documents
    Downloads
    ```


4. Type following code to go to Documents folder.

    `cd` represents "change directory" in this command. Replace [user_name] with the name of the main disk of your computer. You can find this name in Startup Disk menu at System Preferences.

    ```
    cd /Users/[user_name]/Documents
    ```

!!! note

    Ensure you type folder names correctly, including proper capitalization.

### Open a file and folder

5. Type `open .` to open your current located folder
   
    When you open a folder, you can use both relative path and absolute path. It means you can use both command line below.
    ```
    open .
    ```

    ```
    open /Users/[user_name]/Documents
    ```


6. Type `open [file_name.extension]` to open a file

    When you open a file, you need to specify which file you want to open. Also, you need to be located in a same folder of the file is in. For example, if you want to open `agenda_note_team01.txt` file in `Documents` folder, your action will be:

     a. Type following command to navigate your locatiion: `cd /Users/[user_name]/Documents`

     b. Type following command to open the file: `open agenda_note_team01.txt`

!!! note

    When you try to open a file, do not forget to type a extension also. You should type file name, period, extension.

!!! tip

    If you want to open a Visual Studio Code in a project folder, change your current located folder to a your project folder in Terminal. Type `code .`, then Visual studio Code will be opened in your project folder.

## Conclusion

In this section covered how to check your current located folder, and how to see the list of files and folders in your computer through the Terminal. Then, navigated to the destination folder, executed two ways of open it. :partying_face:
