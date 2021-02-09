## Merge

Merge basically integrates code from specific branches to a current branch.

Example: We have a Feature branch based off master branch, after some development on the feature branch using merge command we can merge the contents of feature branch to the master.


![Git_merge_1](/Images/merge_1.png)

![Git_merge_2](/Images/merge_2.png)

#### Git merge workflow

##### Following is the basic merge workflow using git commands

- Create a New feature branch
	git branch Feature_1

- Checkout the new branch, so you can add code/content to this branch 
	git checkout Feature_1
	
- Add code/content

- Stage and commit the files
	git add "created/edited_filename.extension"
	git commit -m "Msg:Commited the Feature_1"

- Checkout Master and merge the Feature_1 branch to it
	git checkout master
	git merge Feature_1
	
- Verify the master branch in the repository, it should have your content/code from Feature_1