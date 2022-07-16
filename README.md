## Git Example
This is a remote repository example

1) To start a git repository

	git init

2) git init will create a folder called ".git" in that folder it will track all the changes happening in that Working Folder

3) Git strauctured the checkin process as follows

	a) Working directory (This is the folder that you are working locally)
	b) What ever changes you are making needs to go to "staging" stage. For that you will be adding / deleting the files using git command. For example to add you use 

		git add "my-file-name.txt"
	c) if you want to clean up changes in teh staging area and want your working folder exactly same as the commit folder (local repositoty), you will execute the following commands ine after other
		i. git reset --hard  (This command take out all changed from the staging area)
		ii. git clean -fdx  (This command will clean any changes that is in working directory and clean for ever)

	d) To move changes from the staging area to the local repository we use the following command

		git commit -m "this '-m' is a switch represents message. We need a message to commit a change so that the repository can track why we made that change"
