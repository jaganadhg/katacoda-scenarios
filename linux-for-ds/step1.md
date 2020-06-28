Let's learn how to create a directory and list the contents of a directory.

## Task
Let's try to list the contents of the current working directory.

`ls`{{execute}}

There is no content in this directory. Let's create an empty directory called my_dir.

To create a directory, run the command mkdir. The command is easy to remember mk stands for make and dir for the directory.

`mkdir my_dir`{{execute}}

Now let's list the contents of the same directory.

`ls`{{execute}}

Now the command lists all the directories in the present working directory.

## ProTip!
If you would like to see all the contents of the present directory with details, 'll' is a handy command.

'll `{{execute}}

# Fun Tip!
Execute the below command to see the results. You could learn a new command sequence!

`type ll`{{execute}}

# Secret
What if there is a hidden file in the directory? You might have observed that some of the folders or files start with a '.'. Those are considered as hidden files. To list them explicitly, use the -a flag.

`ls -a`{{execute}}

# Reference for advanced tricks

http://linuxcommand.org/lc3_man_pages/ls1.html

https://www.cyberciti.biz/faq/ls-command-sort-the-output-by-last-modified-time-date/



