SHELL PERMISSIONS

List of scripts and descriptions

0-iam_betty : Switches the current user to the user betty.
1-who_am_i : prints the effective username of the current user.
2-groups : Prints all the groups the current user is part of.
3-new_owner : Changes the owner of the file hello to the user betty.
4-empty : Creates an empty file called hello.
5-execute : Adds execute permission to the owner of the file hello.
6-multiple_permissions : Adds execute permission to the owner and the group owner, and read permissioin to other user, to the file hello.
7-everybody : Script that give full execute permission to everybody on the file hello.
8-james_bond : Sets the permissions to the file hello as follows:
    Owner : no permission at all
    Group : no permission at all
    Other users : all the permissions

9-John_Doe : Sets the mode of the file hello to -rwxr-x-wx
10-mirror_permissions : Sets the mode of the hello same as olleh's mode.
11-directories_permissions : Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12-directory_permissions : Creates a directory called dir_holberton with permissions 751 in the working directory.
13-change_group : Changes the group owner to holberton for the file hello.