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
| git log | Check logs of your alterations, use "-p" flag to see a particular alteration of your archive |
| git checkout [HASHLOG] | Roll back to a particular alteration |
