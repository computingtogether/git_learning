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