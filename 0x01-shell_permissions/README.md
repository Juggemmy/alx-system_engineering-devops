su betty-a script that switches the current user to the user betty.
id -un -a script that prints the effective username of the current user.
groups -a script that prints all the groups the current user is part of.
chown betty hello - a script that changes the owner of the file hello to the user betty.
touch hello -  a script that creates an empty file called hello
5-execute - a script that adds execute permission to the owner of the file hello.
6-multiple_permissions -a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7- chmod ugo+x hello - a script that adds execution permission to the owner, the group owner and the other users, to the file hello
8-chmod 007 hello - a script that sets the permission to the file hello
9- chmod 753 hello -  a script that sets the mode of the file hello to -rwxr-x-wx
10 - chmod --reference=olleh hello
11 - chmod -R ugo+X - a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12- mkdir -m 751 my_dir - Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13 - chgrp school hello - a script that changes the group owner to school for the file hello
100- chown -hR vincent:staff . - a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory. 
