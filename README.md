

Tech201-git-github

### Making a directory on a local machine and pushing it to GitHub
* Lets create our Markdown file
* Use "mkdir" to create a directory
* Use "cd" <directory name> to move into the directory (can use tab to autocomplete)
* Check which directory you are in by using command "pwd"
* To clone the git directory into local machine, copy repository link
* Then on the local terminal, use "git clone" <url> and press enter
* Double check by using "ls" to check directories
(Can use command "clear" to clean out the terminal)
* Navigate into new directory using "cd"
* Using "ls" should view the one file there - README.md
* Use command "nano" to edit the target file in the syntax- nano <file name>
* Once finished editing inside, press CTRL + X , then Y, then ENTER
(When in git bash nano, use arrow keys to move cursor)
* Edited file contents can be viewed using cat command-> cat <file>
* Add the file using git add . (the . adds all available files)
* Use git status command to see files which are ready to be committed
* Use git commit -m "describe the change"
* Use git push -u (u stands for upstream) origin main ("main" is the target branch)


![](git.png)
