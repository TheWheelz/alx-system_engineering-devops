Welcome to Shell permissions.
0-iambetty - This creates an executable file to change the user to betty
1-whoami - this prints out the current user of the command
2-groups - This prints out the group
3-newowner - THis changes the ownership of the file to betty
4-empty - This creates an empty file called hello with the touch command
5-execute - This add execution permission to the owner
6-multiplepermissions - This add execution permission to the owner, group and adds read permision to others
7-everybody - This gives everybody the execution permission
8-JamesBond  - This set the user and group to no permision given others all the permission 007.
9-JohnDoe  - This set the user to all permision and group to read and execute while the others to only write and execute.
10-mirrorpermissions - Referencing the files to each other by assigning the permission mode of a file to the other.
11-directories permissions - This adds permissions to all subdirectories with the flag -R and the current working directory.
12-directorypermissions - This creates a scripts that makes a directory and assigns a mode with the '-m' flag of permissions
13-changegroup - Changes the group owner of hellow to school
100-changeownerandgroup - Changes the owner and group owner of all the files in the directory with the wild card.
101-symboliclinkpermissions - changes the ownership of the file with the -h flag to specify the particular file _hellow
