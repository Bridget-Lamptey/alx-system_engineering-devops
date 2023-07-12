# Shell, I/O Redirections and filters
#This README file contains several bashscripts and what they do.
* *echo 'Hello, World* prints “Hello, World” to the standard output.
* *echo "\"(Ôo)'"* displays confused smiley, "(Ôo)'.
* *cat /etc/passwd* displays the content of the /etc/passwd file.
* *cat /etc/passwd /etc/hosts* displays the content of /etc/passwd and /etc/hosts.
* *tail -n 10 /etc/passwd* displays the last 10 lines of /etc/passwd
* *head -n 10 /etc/passwd* displays the first 10 lines of /etc/passwd
* *head -n 3 iacta | tail -n 1* displays the third line of the file iacta
* *echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\)*  creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School
* *ls -la > ls_cwd_content* writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

* *tail -n 1 iacta >> iacta* duplicates the last line of the file iacta

* *find ./* -type f -name "*.js" -delete* deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

* ```find ./* -type d | wc -l``` counts the number of directories and sub-directories in the current directory

* ```ls -t | head``` displays the 10 newest files in the current directory, one file per line, sorted from newest to oldest.

* ```sort | uniq -u``` takes a list of words as input and prints only words that appear exactly once, one line, one word, in sorted format.

* ```grep -e root /etc/passwd``` displays lines containing the pattern "root" from the file /etc/passwd

* ```grep -c bin /etc/passwd``` diplays the number of lines that contain the pattern “bin” in the file /etc/passwd
