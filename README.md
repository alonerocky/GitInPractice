git init
git status
git add file
git add '*.txt'
git commit -m 'commit message'
git log
git shortlog -s -n

git remote add remote_name remote_repository
	e.g.git remote add origin https://github.com/try-git/try_git.git
—————————————
Pushing Remotely
The push command tells Git where to put our commits when we're ready, and boy we're ready. So let's push our local changes to our origin repo (on GitHub).

The name of our remote is origin and the default local branch name is master. The -u tells Git to remember the parameters, so that next time we can simply run git push and Git will know what to do. Go ahead and push it!

git push -u origin master

****************************
Pulling Remotely
Let's pretend some time has passed. We've invited other people to our github project who have pulled your changes, made their own commits, and pushed them.

We can check for changes on our GitHub repository and pull down any new changes by running:

git pull origin master

****************************


git diff HEAD
git diff —staged

****************************



1, git commit

2, git rebase

3, git cherry-pick

4, git branch

5, git checkout

6, git remote

7, git push

8, git pull
