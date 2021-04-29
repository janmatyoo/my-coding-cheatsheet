# My Coding Cheatsheet
Contains all the helpful cheatsheet from various technologies!

# Table of contents
1. [Python](#python)
2. [Shell](#shell)
3. [Git](#git)


<img src="https://user-images.githubusercontent.com/30590564/116572548-a66a8f80-a93e-11eb-8729-1bb41a23b2fb.png" width="25" height="25">
## Python 
### Virtual Environment
* `python3 -m venv <venv>` Create new virtual environment
* `source <venv>/bin/activate` Activate in Mac
* `<venv>\Scripts\activate.bat` Activate in Windows
* `deactivate` Deactivate virtual environment

<img src="https://user-images.githubusercontent.com/30590564/116575936-afa92b80-a941-11eb-8298-ddbcfd96ec96.png" width="25" height="25">
## Shell
### File Manipulation
* `cp <source-path>/<filename.filetype> <target-path>/<filename.filetype>` copies a file from one place to another
* `cp <filename.filetype> <filename.filetype>` can create a new copy of a file in the same location with a different filename or different file type
* `man cp` Displays the manual file for the cp command. When viewing a manual file, type q to quit and return to the command line.
* `mv blah.txt /home/user/newdir/` Moves the file called blah.txt to the directory /home/user/newdir/
* `mv blah.txt blahblah.txt` Renames the file blah.txt to blahblah.txt.
* `chmod 755 file.php` Changes the permissions on file.php to 755 (rwxr-xr-x).
* `chown website:website file.php` Changes the file.php so that it is owned by the user and group called website.
* `rm -f oldindex.php` Deletes the file called oldindex.php.
* `rm -rf olddirectory/` Deletes the directory/folder called olddirectory.
* `cat index.php` Displays the entire contents of the file index.php.

### Directory
* `pwd` Displays your location in the directory tree (path)
* `cd ~` Changes to your user’s home directory
* `cd –` Returns you to the previous directory you were working in
* `cd ..` Moves you one directory up/back in the directory structure
* `ls` Display directories
* `ls -l` Display directory contents in a “long list” format.
* `ls -lah` Display all files, including hidden, with a human-readable file size.

### Others
* `grep user@domain.com /var/log/exim_mainlog` Searches the file exim_mainlog for all instances of the e-mail address user@domain.com.
* `wget http://domain.com/file.tar.gz` Pulls the file ‘file.tar.gz’ from the domain ‘domain.com’
* `tail -n 50 /var/log/exim_mainlog` Displays the last 50 lines of the file exim_mainlog.
* `tail -f /var/log/exim_mainlog` Persistently watches the file exim_mainlog as the server makes changes to it (real-time).
* `w` Displays a list of users who are logged in to the system through a remote shell or local terminal, what they are doing, and other relevant information.
* `sudo lsof -i :5955` Find out the process ID (PID) which is occupying the port number (e.g., 5955) you would like to free
* `kill PID` Kill the process which is currently using the port using its PID






