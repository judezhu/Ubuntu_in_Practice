## Import existing source code to github:

 1.Create the remote repository, and get the URL such as git@github.com:/youruser/somename.git or https://github.com/youruser/somename.git

 If your local GIT repo is already set up, skips steps 2 and 3

 2.Locally, at the root directory of your source, git init

 3.Locally, add and commit what you want in your initial repo (for everything, git add . then git commit -m 'initial commit comment')

 4.to attach your remote repo with the name 'origin' (like cloning would do)
git remote add origin [URL From Step 1]

 5.Execute git pull origin master to pull the remote branch so that they are in sync.

 6.to push up your master branch (change master to something else for a different branch):

		git push origin master



