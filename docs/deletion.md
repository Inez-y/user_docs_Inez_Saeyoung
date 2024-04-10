# Deletion

## Overview

Our goal of this section is go to a destination folder, and delete a folder and a file. To do that, first, navigate to a destination folder. Second, execute deletion command for a file and for a folder separately through the Terminal. Finally, we will check the deletion of the folder and file.

!!! warning

    Be careful. Deletion through the command line is permanent. Deleted files can not be restored.


### Navigate to Documents folder 

1. Type `cd /Users/[user_name]/Documents` on the Terminal to navigate `Documents` folder.

2. Type `pwd` to confirm your current location. If you are in the `Documents` folder, proceed to the next step.


### Delete a folder and file

1. Type `ls` to see the list of files or folders in your current location. 

    The result of `ls` will be printed in the Terminal similar with below.

    ```
    test_folder		 	   test_file.txt
    term2			       2216_agenda.pdf
    ```

2. Type `rm test_file.txt` to delete a file.

    `rm` stands for `remove` in this command. After `rm` command line you should specify which file you want to delete. You can use both relative path and absolute path.

    a. Relative path by using file name and extension: `rm test_file.txt`

    b. Absolute path by writing from a root file: `rm /Users/[user_name]/Documents/test_file.txt`

3. Type `rmdir test_folder` to delete a folder.

    `rmdir` stands for `remove folder` in this command. Same with a file, you can use both relative path and absolute path. 

    a. Relative path by using file name and extension: `rmdir test_folder`

    b. Absolute path by writing from a root file: `rm /Users/[user_name]/Documents/user_folder`

4. Type `ls` again to confirm the deletion of file and folder.


## Conclusion

Now you can navigate, create, and delete a file or a folder through the command line on the terminal! :partying_face: These are very basic jobs you can do through the command line. You can explore further on [Apple macOS command line](https://ss64.com/mac/)
