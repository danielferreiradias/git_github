# Git - Essential Commands
- Below is the list of essential commands we need



|     Commands                 |    Description                                  |
| ------------------------------- | --------------------------------------------- |
| git config --list | List git configuration |
| git config --global user.name "My Name" | Git configure username store in "~/.gitconfig" |
| git config --global user.mail myemail@mail.com | Git configure email |
| git config --global core.editor vim | Git configure editor, if you use "--system" flag becomes a global scope for all users |
| git config --global init.defaultBranch main | Git set branch |
| git init | Creates a new git repository |
| git status | Verify your status repository |
| git add [ARCHIVE] | Add tracked archives in 'stage area' |
| git reset | Remove tracked archives in 'stage area' |
| git reset --soft HEAD~1 | Remove the last commit maintaining last configurations untracked |
| git reset --hard | Remove last commit by discarding changes |
| git commit -m "Put your commit message here" | Is used to save your changes to the local repository, use "-a" flag to add in "stage area" |
| git log | Check logs of your alterations, use "-p" flag to see a particular alteration of your archive. Use the "--online" flag to see in an shorter visualization. Use the "--stat" flag to see a number of alterations/exclusions. Use the "-n 2" flag to see the two last alterations. Use the "--graph" flag to see a graph visualization. Use the "--author=XXX" flag to see changes of specific author. Use the "--after="1 week ago" flag to see commits done in this week |
| git checkout [HASHLOG] | Roll back to a particular alteration |
| git branch feature/new_archive | Create a new branch |
| git branch | List available branches, use the flag "-r" for list it |
| git checkout feature/new_archive | Change branch, use a "-b" flag for create a new branch |
| git branch -m feature/new_text_archive | Rename branch |
| git branch -d feature/new_text_archive | Delete branch, use "-D" flag if you did a commit it |
| git merge feature/new_archive | Merge your branches |
| git rebase feature/new_archive | Rebase your branches, be careful because it's history rewriting don't use it in you "main/master" branch |
| git cherry-pic [HASHLOG] | Take a commit that is on another branch and merge it with a current branch. It's need the HASHLOG (git log) of the desired commit |
| git tag | List tags of your repository |
| git tag -a [MY_TAG] -m "Message of MY_TAG" | Create tag |
| git tag -a [MY_TAG] -m "Message of MY_TAG" [HASHLOG] | Apply a tag to a specifit commit |
| git show [MY_TAG] | Shows you the commit that received your tag  |
| git tag -d [MY_TAG] | Delete your tag  |



# GitHub - Essential Commands
- Below is the list of essential commands we need



|     Commands                 |    Description                                  |
| ------------------------------- | --------------------------------------------- |
| git remote add origin git@github.com:danielferreiradias/git_github.git | Add a remote repository of name "origin" |
| git branch -M main | Rename your branch for "main" name |
| git push -u origin main | Push your branch from origin to "main" branch |
| git push --set-upstream origin [YOUR_NEW_BRANCH] | Push your new branch from local to remote repository |
| git pull | The git pull command is used to fetch and download content from remote repositories and immediately update the local repository so that the contents are the same |
| git fetch origin | Downloads commits, files, and refs from a remote repository into your local repo without changes (is more smoothier than "git pull") |
| git diff main origin/main | View the difference between your local "main" with remote "main" repository |


