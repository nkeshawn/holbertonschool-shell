0. alias ls="rm -f *": script that creates an alias *NO SPACES!
1. echo "hello $USER": prints hello user, where user is the current Linux user.
2. export PATH+=":/action": Add /action to the PATH. /action should be the last directory.
3. echo $PATH | tr ':' '\n' | grep -v '^$' | wc -l: counts the number of directories in the PATH. *REMOVE empty lines!
4. env: lists environment variables.
5. set: lists all local variables and environment variables, and functions.
6. BEST="School": creates a new local variable.
7. export BEST="School": creates a new global variable.
8. echo $((TRUEKNOWLEDGE+128)): prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line. *echo automatically adds a new line!
9. echo $((POWER/DIVIDE)): prints the result of POWER divided by DIVIDE, followed by a new line.
10. echo $((BREATH**LOVE)): displays the result of BREATH to the power LOVE.

