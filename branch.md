git branch -r | shows all remote branches
           -a |           remote & local branches
git branch    | without any parameters shows only local branches


git branch -d branch-name-1  
	LOCAL
	remove branch, you must be on the different branch

	When branch is removed there is no sign in master branch that this removed feature branch
	is his parent - history will be updated so to speek.
	
	When branch that you want to remove has unique commits... just read this sentences from the Stack Overflow:
	"It means the branch you are about to delete contains commits that are not reachable from any of: its upstream branch, or HEAD (currently checked out revision). In other words, when you might lose commits¹."

git push origin --delete branch-name-1
	REMOTE

git branch -vv
	To display mapping local branches with remote branches

git branch feature/1234 develop
	when you are on the branch feature/123123 but you want to create new one which base on different branch.

--------------------------------------------------------

git checkout -b some-branch-name-1  |  creates new branch

git push --set-upstream origin testing-branch-1

when there is no remote branch 

--------------------------------------------------------

git status -sb    |   short info  

## How to change remote branch

TODO 


