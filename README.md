

Tech201-git-github

### Making a directory on a local machine and pushing it to GitHub
* Lets create our Markdown file
* Use "mkdir" to create a directory
* Use `cd directory name` to move into the directory (can use tab to autocomplete)
* Check which directory you are in by using command `pwd`
* To clone the git directory into local machine, copy repository link
* Then on the local terminal, use `git clone <url>` and press enter
* Double check by using `ls` to check directories
(Can use command `clear` to clean out the terminal)
* Navigate into new directory using `cd`
* Using `ls` should view the one file there - README.md
* Use command `nano` to edit the target file in the syntax- `nano <file name>`
* Once finished editing inside, press `CTRL + X` , then `Y`, then `ENTER`
(When in git bash nano, use arrow keys to move cursor)
* Edited file contents can be viewed using cat command-> `cat <file>`
* Add the file using `git add .` (the . adds all available files)
* Use `git status` command to see files which are ready to be committed
* Use `git commit -m "describe the change"`
* Use `git push -u origin main`, (u stands for upstream) ("main" is the target branch)

### Using the Pycharm method
* Clone the repository into your PyCharm terminal using `git clone`
* Once you've completed the edits, with the file you edited follow these steps:
* Right click -> Git -> add (the file name should be green, meaning it is ready to commit)
* On the left side of the application, click the commit tab and tick the box for the file you want to push
* In the chat box below, add your commit comments then click commit
* Committed files can be visualised by clicking the git logo in the bottom left corner of PyCharm
* To push, click the upward green arrow, edit target branch as needed, then click push.


![](git.png)
