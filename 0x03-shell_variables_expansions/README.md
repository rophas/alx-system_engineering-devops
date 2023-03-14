#!/bin/bash
alias ls="rm *" Create a script that creates an alias. Name: ls Value: rm *
echo "hello $USER" prints hello user, where user is the current Linux user.
export PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $PATH | grep -o ":/" | wc -l | awk '{print $1+1}' counts the number of directories in the PATH
