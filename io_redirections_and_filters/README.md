0. echo "Hello, World": prints "Hello, World", followed by a new line to the standard output.
1. echo "\"(Ôo)'": displays a confused smiley
2. cat /etc/passwd: displays the content of the /etc/passwd file.
3. cat /etc/passwd /etc/hosts: displays the content of /etc/passwd and /etc/hosts
4. tail /etc/passwd: displays the last 10 lines of /etc/passwd.
5. head /etc/passwd: displays the first 10 lines of /etc/passwd.
6. head -n 3 iacta | tail -n 1: displays the third line of the file iacta. (without using sed)
7. echo "Best School" > '\'\*\\\'\"Best School\"\\'\\*$\?\*\*\*\*\*:)': creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School. REMEMBER to add \ to all single and double quotation marks.
8. ls -la > ls_cwd_content: writes into the file ls_cwd_content the result of the command ls -la.
9. tail -n 1 iacta >> iacta: duplicates the last line of the file iacta.
10. find . -type f -name "*.js" -delete: deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. find . -mindepth 1 -type d | wc -l: counts the number of directories and sub-directories in the current directory.
12. find . -maxdepth 1 -type f | ls -t | head -n 10: displays the 10 newest files in the current directory.
13. sort | uniq -u: takes a list of words as input and prints only words that appear exactly once. REMEMBER order matters - sort before using command uniq.

