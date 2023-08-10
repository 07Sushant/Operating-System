# Linux Commands Execution

## Commands

1. `echo "Sum is $b"`
   - Action: Prints the value of variable 'b' along with the text "Sum is".

2. `wc < 2.txt`
   - Action: Counts the lines, words, and characters in the file '2.txt' using input redirection.

3. ```
   x=2
   y=3

Action: Assigns the values 2 to 'x' and 3 to 'y'.

let "a=$x+$y"
b=`expr $x + $y`
echo "Sum is $a"
echo "Sum is $b"


Action: Calculates the sum of 'x' and 'y', storing it in 'a', and using 'expr' to store the sum in 'b'. Prints both results.
touch if_else.sh

Action: Creates an empty shell script file named 'if_else.sh'.
nano nano.sh

Action: Tries to open a shell script file named 'nano.sh' for editing using the 'nano' editor (assuming typo).
nano if_else.sh

Action: Opens the shell script file 'if_else.sh' for editing using the 'nano' editor.
./if_else.sh 2 10

Action: Attempts to execute the shell script 'if_else.sh' with arguments 2 and 10, but gets "Permission denied" due to lack of execution permission.
chmod +x if_else.sh

Action: Changes the permissions of 'if_else.sh' to make it executable.
./if_else.sh 2 10

Action: Executes the modified 'if_else.sh' script with arguments 2 and 10 after changing permissions. Displays relevant output based on the script.


echo "value_of 2"
echo "value_of 10"


echo "value_of 2"
echo "value_of 10"


Files Created with the ".sh" Extension
if_else.sh
nano.sh (assuming typo)


Created by [Sushant](https://github.com/07Sushant)




