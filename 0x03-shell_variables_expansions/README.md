Create a script that creates an alias.

Name: ls
Value: rm *
julien@ubuntu:/tmp/0x03$ ls
0-alias  file1  file2
julien@ubuntu:/tmp/0x03$ source ./0-alias 
julien@ubuntu:/tmp/0x03$ ls
julien@ubuntu:/tmp/0x03$ \ls
julien@ubuntu:/tmp/0x03$ 
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 0-alias
 
1. Hello you
mandatory
Create a script that prints hello user, where user is the current Linux user.

julien@ubuntu:/tmp/0x03$ id
uid=1000(julien) gid=1000(julien) groups=1000(julien),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),113(lpadmin),128(sambashare)
julien@ubuntu:/tmp/0x03$ ./1-hello_you 
hello julien
julien@ubuntu:/tmp/0x03$ 
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x03-shell_variables_expansions
File: 1-hello_you
