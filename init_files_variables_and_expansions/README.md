0. alias ls="rm -f *": script that creates an alias *NO SPACES!
1. echo "hello $USER": prints hello user, where user is the current Linux user.
2. export PATH+=":/action": Add /action to the PATH. /action should be the last directory.
3. echo $PATH | tr ':' '\n' | grep -v '^$' | wc -l: counts the number of directories in the PATH. *REMOVE empty lines!
