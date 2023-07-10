#This file contains what each script is in the 0x01-shell_permissions directory is doing
0-iam_betty script switches the current user to the user betty 
The script in 1-who_am_i prints the effective username of the current user
2-groups script prints all the groups the current user is part of
3-new_owner script changes the owner of the file hello to the user betty
4-empty script creates an empty file called hello
5-execute script adds execute permission to the owner of the file hello
6-multiple_permissions script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7-everybody script adds execution permission to the owner, the group owner and the other users, to the file hello
8-James_Bond gives no permission to owner and group but grants other users all permissions
9-John_Doe script change permissions to -rwxr-x-wx for file hello
10-mirror_permissions sets the mode of the file hello the same as olleh’s mode
11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12-directory_permissions script creates a directory called my_dir with permissions 751 in the working directory
