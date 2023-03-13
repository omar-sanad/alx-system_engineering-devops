Hello World : A script that prints Hello, World, followed by a new line to the standard output.
Confused smiley : A script that displays a confused smiley: "(Ôo)'.
Let's display a file : A script that displays the content of the /etc/passwd file.
What about 2? : A scipt that displays content of /etc/passwd and /etc/hosts.
Last lines of a file : A script that displays the last 10 lines of /etc/passwd.
I'd prefer the first ones actually : A scipt that displays the first 10 lines of etc/passwd.
Line #2 : A script that displays the third line of the file iacta.
The file iacta will be in the working directory and you are not allowed to use sed.
It is a good file that cuts iron without making a noise : A script that creates a file named exactly \*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:) containing the text Holberton School ending by a new line.
For this challenge, remember to use a single backslash \ to escape special characters and double backslash \\ to escape the backslash itself.
Save current state of directory : A script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_contentdoes not exist, create it.
Duplicate last line : A script that duplicates the last line of the file iacta.
No more javascript : A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
Don't just count your directories, make your directories count : A script that counts the number of directories and sub-directories in the current directory.
The current and present directories should not be taken into account.
Hidden directories should be counted.
Solution: mindepth 1 ; To exclude root directory
Others: maxdepth 1 ; To avoid parsing sub directories. (you may need this in future.)
Whats12's new : A script that prints the 10 newest files in the current directory.
The output should be; one file per line and sorted from the newest to the oldest.
Being unique is better than being perfect : A script that takes a list of words as input and prints only words that appear exactly once.
Input and Output format is; One word per line.
Words should be sorted. (use this list as your input to see if the challenge will work. 😊) cat list | ./13-unique
It must be in that file : A script that prints lines containing the pattern "root" from the file /etc/passwd.
Count that word : A script that displays the number of lines that contain the pattern "bin" in the file /etc/passwd.
What's next? : A script that containing the pattern "root" and 3 lines after them in the file /etc/passwd.
B : This shows the lines before your pattern match.
A : This shows the lines after your pattern match.
I hate bins : A script that displays all the lines in the file /etc/passwd that do not contain the pattern "bin".
Letters only please : A script that displays all lines of the file /ect/ssh/sshd_config starting with a letter, including capital letters as well.
This also works : grep ^[[:alpha:]] /etc/ssh/sshd_config
A to Z : A script that replaces all characters A and C from input to Z and E respectively.
Without C, you would live in hiago : A script that removes all letters c and C from input.
esreveR : A script that reverse its input.
DJ Cut Killer : A scipt that displays all users and their home directories, sorted by users, based on the /etc/passwd file.
