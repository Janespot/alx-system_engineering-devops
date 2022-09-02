#1/bin/bash
0. 0-iam_betty
Create a script that switches the current user to the user betty.
You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script

1. 1-who_am_i
Write a script that prints the effective username of the current user.

2. 2-groups
Write a script that prints all the groups the current user is part of.
Note: depending on the user, you will get a different output.

3. 3-new_owner
Write a script that changes the owner of the file hello to the user betty

4. 4-empty
Write a script that creates an empty file called hello.

5. 5-execute
Write a script that adds execute permission to the owner of the file hello.
The file hello will be in the working directory

6. Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
The file hello will be in the working directory

File: 6-multiple_permissions

    

7. Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

The file hello will be in the working directory
You are not allowed to use commas for this script

File: 7-everybody

    

8. Write a script that sets the permission to the file hello as follows:

Owner: no permission at all

Group: no permission at all

Other users: all the permissions

The file hello will be in the working directory You are not allowed to use commas for this script

File: 8-James_Bond

    

9. Write a script that sets the mode of the file hello to this:
The file hello will be in the working directory
You are not allowed to use commas for this script

File: 9-John_Doe

    

10. Write a script that sets the mode of the file hello the same as olleh’s mode.
The file hello will be in the working directory
The file olleh will be in the working directory
Note:the mode of olleh will not always be 664. Make sure your script works for any mode.

File: 10-mirror_permissions

    

11. Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

File: 11-directories_permissions

    



12. Create a script that creates a directory called my_dir with permissions 751 in the working directory.

File: 12-directory_permissions

    

Write a script that changes the group owner to school for the file hello
The file hello will be in the working directory

File: 13-change_group

    

13. Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

File: 100-change_owner_and_group

    



14. Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.
The file _hello is in the working directory
The file _hello is a symbolic link

File: 101-symbolic_link_permissions

    


15. Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
The file hello will be in the working directory

File: 102-if_only

    


16. Write a script that will play the StarWars IV episode in the terminal.

File: 103-Star_Wars
