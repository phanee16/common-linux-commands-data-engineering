# common-linux-commands-data-engineering

## A few examples of common Linux commands for Data Engineering

### Useful Commands:
Time and Date:
- cal
- date

Disk Usage or File Size:
- df -h
- du -sh*

System Performance:
- top

### Using the Shell
Exploring:
- pwd
- ls -lah
- cd /tmp cd ~
- which python3

Viewing Files:
- less /etc/password
- cat /etc/password

Counting lines:
- wc -l /etc/passwd

### Modify Files and Directories 
- touch newfile.txt
- mkdir newdir
- mkdir -p moredir/dir1/dir2
- rm -rf moredir

### Processes
- ps
- ./sleeper.sh &
- fg 1


### Goal: Learn the basics of Linux Shell
Let's practice some common shell commands

Part 1: Navigate the file system
#### Create a directory foo via mkdir foo command
cd into the foo directory
Part 2: Create a file with touch
#### Create a file using touch newfile.txt
Run the command again? What happens?
Part 3: Remove files and directories
#### Remove the directory foo via the command rm -rf foo
Make a file and then delete it: touch bar.xt then run rm bar.txt
Part 4: List files
list the contents of /usr/bin by running the command ls -l /usr/bin
What did you see?


