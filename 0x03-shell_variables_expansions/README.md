#!/bin/bash
alias ls="rm *" Create a script that creates an alias. Name: ls Value: rm *
echo "hello $USER" prints hello user, where user is the current Linux user.
export PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $PATH | tr : '\n' | grep -v '^$' | wc -l counts the number of directories in the PATH   
printenv lists environment variables.
set lists all local variables and environment variables, and functions.
BEST="School" creates a new local variable. Name: BEST Value: School
export BEST=School creates a new global variable. Name: BEST Value: School
echo $(($TRUEKNOWLEDGE + 128)) prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER / $DIVIDE)) prints the result of POWER divided by DIVIDE, followed by a new line. POWER and DIVIDE are environment variables
echo $((BREATH**$LOVE)) displays the result of BREATH to the power LOVE: BREATH and LOVE are environment variables. The script should display the result, followed by a new line
printf "%d\n" "2#$BINARY" converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable BINARY. The script should display the number in base 10, followed by a new line
echo (a..z)(a..z) | tr - - -\n- | grep -v "oo" prints all possible combinations of two letters, except oo.  Letters are lower cases, from a to z  One combination per line   The output should be alpha ordered, starting with aa   Do not print oo   Your script file should contain maximum 64 characters
