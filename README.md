1-Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
“ls -a” to look for a hidden .git folder
“git status” or git + any command but “help”


2-Assuming that you are currently within a Git repository, write the command (or commands) that will create a new file named 'hello-world.txt' then stage and commit it.
touch hello-world.txt
git add hello-world.txt
“git commit” and then add a commit message
or
“git commit -m ‘commit message comes here’


3-Assuming that you are currently within a Git repository that contains a file named 'README.md', write the command (or commands) that will display any uncommitted changes made to this file.
git diff README.md

4-Assuming that you are currently within a Git repository that includes several commits, write the command (or commands) that will display the changes from the commit with the ID of abc123.
git show abc123

5-Assuming that you are currently within a Git repository that includes multiple commits, write the command (or commands) that will display the IDs and commit messages for the 3 most recent commits.

