# 0x01-shell_permissions
## This readme will contain the meaning of all the commands i will use in this project
### These are the explanations of the different scripts in order

* 0-iam_betty - switch from the current user to a different user
* 1-who_am_i - print the effective username of the current user
* 2-groups - print all groups the current user is a part of
* 3-new_owner - changes owner of a file from one to another
* 4-empty - create an empty file with a given name
* 5-execute - add execute permission to the owner of a specific file
* 6-multiple_permissions -  add execute permission to the owner and the group owner, and read permission to other users, to a specific file
* 7-everybody - add execution permission to the owner, the group owner and the other users, to a file
* 8-James_Bond - sets the permission to a file as follows:
      ** Owner: no permission at all
      ** Group: no permission at all
      ** Other users: all the permissions
* 9-John_Doe - sets the mode of the file to this: -rwxr-x-wx
* 10-mirror_permissions - sets the mode of the file hello the same as olleh’s mode.
      ** The file hello will be in the working directory
      ** The file olleh will be in the working directory
* 11-directories_permissions - a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
* 12-directory_permissions - Create a script that creates a directory called my_dir with permissions 751 in the working directory.
* 13-change_group - a script that changes the group owner to school for the file hello
* 100-change_owner_and_group - a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
* 101-symbolic_link_permissions -  a script that changes the owner and the group owner of _hello to vincent and staff respectively.
      ** The file _hello is in the working directory
      ** The file _hello is a symbolic link
* 102-if_only -  a script that changes the owner of the file hello to betty only if it is owned by the user guillaume
* 103-Star_Wars - a script that will play the StarWars IV episode in the terminal
