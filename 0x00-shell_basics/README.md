# This directory for 0x00.Shell,basics tasks
* **Create bash script 0-current_working_directory to print current working directory path
* Create bash script 1-listit to list the contents of the current directory
* Create bash script 2-bring_me_home to change the current directory to the user's home directory
* Create bash script 3-listfiles to list files in the current working directory in the long format
* Create bash script 4-listmorefiles to list all files including the hidden files in the current working directory in the long format
* Create bash script 5-listfilesdigitonly to list all files including the hidden files in the current working directory in the long format also display gids in digital formats
* Create bash script 6-firstdirectory to create a new directory /tmp/my_first_directory
* Create bash script 7-movethatfile to move the file /tmp/betty to the directory /tmp/my_first_directory
* Create bash script 8-firstdelete to remove the file /tmp/my_first_directory/betty
* Create bash script 9-firstdirdelete to remove the directory /tmp/my_first_directory
* Create bash script 10-back to change directory to the previous one
* Create bash script 11-lists to list all files even the hidden ones in the current directory, the parent directory and the /boot directory
* Create bash script 12-file_type to print the file type of /tmp/iamafile
* Create bash script 13-symbolic_link to create symbolic_link of /bin/ls to the current_working_directory under the name __ls__
* Create bash script 14-copy_html to copy all html files in current directory to the parent directory only update!!
* Create bash script 100-lets_move to move any file starts with uppercase letter to /tmp/u directory
* Create bash script 101-clean_emacs to remove all temp files created by emacs in the current directory [files ends with ~]
* Create bash script 102-tree to create directories welcome/, welcome/to and welcome/to/school in the current directories with only one space character.
* Create bash script 103-commas to list all files in current working directory with the following rules
      Directory names ends with /
      Hidden files and directories are included
      The names is listed in alpha ordered while . and .. listed at the beginning
      Names start with digit come first then letters
* Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.**


## Compiling The Magic File
file -C -m school

this will compile the source school and generates binary file school.mgc
To use the binary file

file -m school.mgc * or file --mime-type -m school.mgc *

