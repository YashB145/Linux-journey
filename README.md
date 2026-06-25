# Linux-journey 
Starting off my Linux journey and updating about what I implemented on my learning path.
 
# Day 1- LINUX BASICS.
## Starting with linux commands  

1. echo- used to print anything in " ".
2. whoami- displays the current user.
3. pwd- prints the working directory


# Day 2
1. cd- change directory
2. touch- used to create an empty file
3. clear- clears the terminal


# Day 3
1. Timestamp--> $date
2. Sorting--> ls -s -->shows list of files and allocated space
              ls -lS --> sorts files by size, largest first
3. Formatting--> ls --format=commas --> separates file name by commas.
                 ls -lQ --> prints file name in quotes/short form

4. extras:
   ls -ald --> prints directories only
   ls -al --author --> prints username of creator of file


# Day 4- THE 'man' COMMAND
1. 'man man'--> opens the manual page.
2. 'man ls'--> lists all the commands with description from manual.
3. 'man intro'--> gives introduction to user commands.
4. 'man -w ls'--> returns location of the file from where page is rendered.

# WORKING WITH DIRECTORIES
## Create directory
1. **mkdir** --> creates new directory.
2. mkdir testdir{01..10}--> creates 10 new directories with prefix testdir.
3. mkdir -p parentdir/ childdir{01..100} --> -p allows the system to create a parent directory.
                                              To view type ls -l parentdir.

## Change directory   
5. **cd**--> change directory, to change directory use: cd dir_name.
6. To get back to home or root directory--> cd, cd $HOME, cd ~, cd /root.

## Remove directory
7. **rmdir** --> remove/ delete directory.
8. To remove any directory --> rmdir dir_name.
9. To remove any directory forcefully --> rm -rf dir_name.


# Day 5- CREATE AND DELETE FILES
1. touch testfile --> creates empty file named testfile.
2. touch my{01..100}file --> creates multiple files with name my01file..... my100file.
3. ls my*file --> displays all files with myFile name.

## Deleting Files
1. rm try01 --> Deletes file try01
2. rm -rf testdir --> forcefully deletes the testdir directory.

## vim
vim is used to create a new file just as touch.

# Day 6- PIPES and REDIRECTIONS
The pipes and redirections are used to send or retrieve some information sent from one command or script to another.
1. grep --> this command searches for a given pattern in the output.
2. wc --> is a utility for counting words, new lines, bytes.
3. sort --> will sort the output in alphabetical order.
