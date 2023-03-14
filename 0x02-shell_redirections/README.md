#!/bin/bash
echo "Hello, World" prints “Hello, World”
echo "\"(Ôo)'" is the script that displays a confused smiley "(Ôo)'
cat /etc/passwd Displays the content of the /etc/passwd file.
cat /etc/passwd /etc/hosts Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd Displays the last 10 lines of /etc/passwd
head -n 10 /etc/passwd Display the first 10 lines of /etc/passwd
head -n 3 iacta | tail -n 1 displays the third line of the file iacta  and ensures The output differs, depending on the content of the file iacta
echo "Best School" > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
echo "ls -la" > ls_cwd_content writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
tail -n 1 iacta >> iacta duplicates the last line of the file iacta
find . -type f -name "*.js" -delete deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d -not -name | wc -l counts the number of directories and sub-directories in the current directory. The current and parent directories and Hidden directories should be counted.
ls -t1 | head -n 10 displays the 10 newest files in the current directory. Requirements: One file per line Sorted from the newest to the oldest
sort | uniq -u script that takes a list of words as input and prints only words that appear exactly once.Input format: One line, one word Output format: One line, one word Words should be sorted
grep -i "root /etc/passwd Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -c -i "bin" /etc/passwd Display the number of lines that contain the pattern “bin” in the file /etc/passwd
