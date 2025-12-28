**Clone repo
	- Clone a repo in git bash/terminal
	- click on the code button click on down arrow copy url for HTTPS
	- you have to clone the repo into a directory, once you do that
	- go to git bash/terminal type git clone and paste url
	- it will now be cloned onto that directory

Creating Branches in GitHub
	- click on the repo click on the main button type in a name and click Create branch "name" from main
	- also can click on the Branch button and click on the green New branch button

Creating Branches Git Bash/Terminal
	- go to that repo, cd into the location of the repo
	- type git branch this shows local branches
	- type git branch -a this will list all branches in the Git repo both local and remote
	- to create a new branch type the command git branch new-branch-name
	- to create the new branch and switch to it type git checkout -b new-branch-name
	- to switch between the branches git checkout branch-name
	- git switch branch-name(newer versions of Git)
	- to delete a branch type git branch -d branch-name
	- to force delete git branch -D branch-name
	- rename branch git branch -m old-name new-name
	- to push this into the repo type git push origin branch-name
	- now it is in the repo

Merge/Pull Request
	- after you make your changes to the branch and want to pull those fixes into the main/master
	- press the Pull request button, then click on the green new pull request button
	- it will show a list of branches along with main/master
	- choose the branch, click on the create new pull request button
	- it will open a page that says Open a pull request
	- Add a description, then click on Create pull request
	- make sure there are no conflicts, if they're fix them
	- then press Merge pull request and Confirm merge
	- if everything is correct the merge

**Note: you have to clone the repo to create branches
