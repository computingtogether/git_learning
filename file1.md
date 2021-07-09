# Git notes

-u flag automatically links your local branch with your remote and you can use git pull without arguments.
it's the same as -set--upstream

**origin**
origin is a shorthand for the remote repository that the project was originally cloned from. 

**squash**

start by going onto branch that you wish to rebase with main and eventually merge.

Then run:

`
git rebase -i HEAD~3
`
~3 is how many commits back you want to amend.

press i to start vim insert mode. change picks to squash for all but one. hit esc then :wq enter to save
now comment out the commit messages that you don't want to see by putting a # to the left. then :wq enter again. 

'git log' --oneline shows all commits
'git reflog' shows all changes
