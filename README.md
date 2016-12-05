## About
This document is for those people who are relatively new to GitHub but know the basic concepts like repositories and commits etc. For experts this document can act as a revision document.<br>
**Happy learning!!**

### Commands
  1. Creating a repository: `git init`<br>
You need to be in the repository that is to be initialised as the git repository<br>

  2. Checking status: `git status`<br>
Command gives the current status of the the repository irrestective of file being commited or not. Status includes whether file is 'tracked' or 'untracked' or 'modified' etc.<br>

  3. Adding file:<br>
		`git add <file_to_add>`	Adds the specified file to staging area<br>
		`git add .`	Adds all untracked files to staging area<br>
		`git add *.<extension>`	Adds all files with the specified extension<br>
**Adding is only done to the staging area and not to the final commit straight away!!**<br>

  4. Making a commit: `git commit`<br>
Command redirects to an editor where you have to specify some description regarding the commit. This commits the files that were present in the staging area only!!<br>

  5. Unstaging a file: `git rm --commit<file_name>`<br>
Removes the file from the staging area  and transfers it back to the modification area.<br>

  6. Changed files:<br>
		`git diff`	Command shows the changes made to the files. Command works only when the file is in the unstaged area.<br>
		For staged files: `git diff --staged`<br>

  7. Pushing to remote repo:<br>
		`git remote add origin <url to the remote repo>`<br>
		`git push -u origin <branch to which pushin is to be done>`<br>

  8. Pulling from your own remote repo to a locally existing repo<br>
		`git pull <url of remote repo> <branch>`<br>
To pull into a local repo the command prompt control needs to be inside the repo<br>
