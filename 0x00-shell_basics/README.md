1- pwd: script that prints the absolute path name of the current working directory
2- ls: Display the contents list of your current directory
3- cd ~: changes the working directory to the user’s home directory
4- ls -l: Display current directory contents in a long format
5- ls -la: Display current directory contents, including hidden files (starting with .). Use the long format
6- ls -lan: Display current directory contents in Long format with user and group IDs displayed numerically And hidden files (starting with .)
7- mkdir /tmp/my_first_directory: creates a directory
8- mv betty /my_first_directory: Move the file betty from /tmp/ to /tmp/my_first_directory
9- rm /temp/my_first_directory/betty: Delete the file betty
10- rm -r /tmp/my_first_directory: Delete the directory my_first_directory that is in the /tmp directory
11- cd -: changes the working directory to the previous one
12- ls -al . .. /boot: lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
13- file /tmp/iamafile: prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script
14- ln -s /bin/ls __ls__: Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
