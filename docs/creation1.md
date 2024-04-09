# How to create a File with Command Line on the Terminal

## Overview

This section will cover how to create a file and folder on your computer through the terminal.

## Create

1. Introducing File Creation Command

    To create a file, you can use the `touch` command followed by the filename:

    ```
    touch [file_name]
    ```

    To create a folder, you can use the `mkdir` command followed by the folder name:

    ```
    mkdir [folder_name]
    ```

2. Common Mistakes and Cautions

    Double-check the filename to avoid errors.
    Be cautious not to overwrite existing files unintentionally.

3. Example of File and Folder Creation

    To create a file named "example.txt," type:

    ```
    touch example.txt
    ```

    To create a folder named "test_documents" type:

    ```
    mkdir test_documents
    ```


5. Type `cd ..` to move out to a parent folder which means higher hierarchy folder
   
    One period (.) means your current located folder. Two period (..) means one level higher folder than your current located folder. This is relative path. We can also use absolute path which we used in step 1 to change your current folder. You can also type this. 
    ```
    cd /Users/[user_name]/Downloads
    ```

!!! note

    Ensure you type folder names correctly, including proper capitalization.
    Be cautious when using relative paths (e.g., cd .. to move up one folder), as it can lead to unintended movements.


## Conclusion

Now you can navigate, create a file or folder on your computer through the command line on the terminal! :partying_face:
