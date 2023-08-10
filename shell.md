# Practical Task 2

Commands Execution

1. Command: echo "Sum is $b"
   Action: Prints the value of variable 'b' along with the text "Sum is".

2. Command: wc < 2.txt
   Action: Counts the lines, words, and characters in the file '2.txt' using input redirection.

3. Command:
   x=2
   y=3
   Action: Assigns the values 2 to 'x' and 3 to 'y'.

4. Command:
   let "a=$x+$y"
   b=`expr $x + $y`
   echo "Sum is $a"
   echo "Sum is $b"
   Action:
   - Calculates the sum of 'x' and 'y', storing it in 'a'.
   - Uses 'expr' to store the sum in 'b'.
   - Prints both results.

5. Command: touch if_else.sh
   Action: Creates an empty shell script file named 'if_else.sh'.

6. Command: nano nano.sh
   Action: Tries to open a shell script file named 'nano.sh' for editing using the 'nano' editor (assuming typo).

7. Command: nano if_else.sh
   Action: Opens the shell script file 'if_else.sh' for editing using the 'nano' editor.

8. Command: ./if_else.sh 2 10
   Action: Attempts to execute the shell script 'if_else.sh' with arguments 2 and 10, but gets "Permission denied" due to lack of execution permission.

9. Command: chmod +x if_else.sh
   Action: Changes the permissions of 'if_else.sh' to make it executable.

10. Command: ./if_else.sh 2 10
    Action: Executes the modified 'if_else.sh' script with arguments 2 and 10 after changing permissions. Displays relevant output based on the script.

11. Command:
    echo "value_of 2"
    echo "value_of 10"
    Action: Prints the text "value_of 2" and "value_of 10" to the console, but there's no prior mention of the 'value_of' command.

12. Command: echo "No_of_arguments: 2"
    Action: Prints the text "No_of_arguments: 2" to the console.

Files Created with the ".sh" Extension:
- if_else.sh
- nano.sh (assuming typo)

Created by Sushant
GitHub: https://github.com/07Sushant
