The scripts are created to give file permissions, change permissions, users, superusers and IDs.

File 0-iam_betty create a script switches a user ID to another (betty)

File 1-who_am_i creates a script that prints the effective user ID of a current user.

File 2-groups creates a script that prints all the groups the current user is part of.

File 3-new_owner creates a script that changes the owner of a file to another user (betty).

File 4-empty creates a  script that creates an empty file (hello).

File 5-execute creates a script that adds execute permission to the owner of a file (hello).

File 6-multilple_permissions creates a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

File 7-everybody creates a script that adds execution permission to the owner, the group owner and other users, to the file (hello).

File 8-James_bond creates script that sets all the permissions to a file (hello). 
File 9-John_Doe creates a script that sets the mode of a file (hello) to be readable, writable, and executable.

File 10-mirror_permissions creates a script that sets the mode of two files to be the same mode.

File 11-directories_permissions creates a script that adds execute permission to all subdirectories of the current directory without changing regular files for the owner, the group owner and all other users.

File 12-directory_permissions creates a script that creates a directory with a specific permission (751) in the working directory.

File 13-change_group creates a script that changes the group owner of a file (hello).

File 100-change_owner_and_group creates a script that changes an owner to (vincent) and a group owner to staff for all files and directories in the working directory.

File 101-symbolic_link_permissions creates a script that changes the owner and the group owner of the file (hello) to vincent and staff respectively.

File 102-if_only creates a script that changes the owner of the file (hello) to another user(betty) only if it is owned by the user guillaume.

File 103-Star_wars creates a script that will play the StarWars IV episode in the terminal.
