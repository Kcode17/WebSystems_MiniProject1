## Branch

![Git_Branch](/Images/branch.PNG)

A branch represents an independent line of development. Branches serve as an abstraction for the edit/stage/commit process. You can think of them as a way to request a brand new working directory, staging area, and project history. New commits are recorded in the history for the current branch.
The git branch command lets you create, list, rename, and delete branches.

### Branch Commands
List all the branches in the repository
	git branch
	
![Git_Branch](/Images/branches.PNG)
	
Create a new branch feature_1
	git branch feature_1
	
Delete the feature_1 branch,provided all the changes are merged back to the main
	git branch -d feature_1
	
Force delete the branch feature_1, irrespecitve of changes being merged back or not
	git branch -D feature_1
