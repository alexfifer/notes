# Git Cheat Sheet

* **status -** `git status` This command will list "Untracked" files (files that may need to be added). It also shows changed files (files that may need to be committed).
* **commit -** `git commit -a -m "A message here"` This command will commit any changes made (to new files that have been added and existing files that have been changed) to your local repository. A message will display that indicates if the commit was successful.
* **push -** `git push` This command results in the files that have been added (or changes that have been committed) being pushed to the global repository as long as there are no conflicts.
* **pull -** `git pull`
  > The git pull command will bring any changes on the server down to your local repository. You should always do this first because changes could have been made to the files on the server, by someone else or by yourself working from another place, since the last time you synchronized the server and the local repository and you want to bring the two into a consistent state before uploading your changes. - Gopalan Nadathur

* **add -** `git add <filename_here>` This command will tell Git to track a file. Newly created files need to be added for Git to track their changes. 
* **config -**  `git config` This command tells Git the configuration of the local level. Executing git config will modify a  text file that contains information about the configuration of a level. i.e. from lab01:

  `% git config --global user.name "YOUR NAME HERE"`
  
  `% git config --global user.email "YOUR UMN EMAIL ADDRESS"`

  `% git config --global core.editor "YOUR EDITOR HERE"`
  
* **clone -** `git clone <filename_here>` This command will clone a directory or file for use at a local level. An example was the cloning of the public repository that we did at the beginning of lab01.
* **remote -** `git remote` This command would be followed by a `git remote add` to manage tracked repositories. Remote commands can also rename, remove, etc. tracked repos.
