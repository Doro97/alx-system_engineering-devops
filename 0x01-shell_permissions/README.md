# Shell permissions
Linux systems are both multitasking and multiuser meaning more than one user can be operating the computer at the same time.

## File permissions
On a Linux system, each file and directory is assigned access rights for the owner of the file, the members of a group of related users, and everybody else

## Permission settings
* rwx rwx rwx = 111 111 111
* rw- rw- rw- = 110 110 110
* rwx --- --- = 111 000 000

*and so on...*

* rwx = 111 in binary = 7
* rw- = 110 in binary = 6
* r-x = 101 in binary = 5
* r-- = 100 in binary = 4

## Common commands
Some of the common commands used include:

1. chmod - modify file access rights
2. su - temporarily become the superuser
3. sudo - temporarily become the superuser
4. chown - change file ownership
5. chgrp - change a file's group ownership

## Files in this folder

|File Name|Description|
|---------|-----------| 
|[0-iam_betty](0-iam_betty)|a script that switches the current user to the user *betty*.| 
|[1-who_am_i](1-who_am_i)|a script that prints the effective username of the current user| 
|[2-groups](2-groups)|a script that prints all the groups the current user is part of.| 
|[3-new_owner](3-new_owner)|a script that changes the owner of the file hello to the user betty.| 
|[4-empty](4-empty)|a script that creates an empty file called hello.| 
|[5-execute](5-execute)|a script that adds execute permission to the owner of the file hello | 
|[6-multiple_permissions](6-multiple_permissions)|a script that dds execute permission to the owner and the group owner, and read permission to other users, to the file hello | 
|[7-everybody](7-everybody)|a script that adds execution permission to the owner, the group owner and the other users, to the file hello| 
|[8-James_Bond](8-James_Bond)|a script that ets the permission to the file hello as follows:    Owner: no permission at all Group: no permission at all  Other users: all the permissions | 
|[9-John_Doe](9-John_Doe)|a script that sets the mode of the file hello to -rwxr-x-wx :| 
|[10-mirror_permissions](10-mirror_permissions)|a script that sets the mode of the file hello the same as olleh’s mode(-rw-rw-r--)| 
|[11-directories_permissions](11-directories_permissions)|a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed| 
|[12-directory_permissions](12-directory_permissions)|a script that creates a directory called my_dir with permissions 751 in the working directory | 
|[13-change_group](13-change_group)|a script that changes the group owner to school for the file hello| 
