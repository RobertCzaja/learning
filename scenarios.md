## 1. When after merge develop/master to feature branch i want to revert this operation. 
	

## 2. When make a commit and try to revert this commit but i want to changes in files remains as "new code". 
		1. When commits were not pushed to remote branch 
		2. When comits were pushed to remote branch  

## 3. When i do my feature shit but i realise that I'm on develop branch 
	(with a few commits - not pushed):
	* move changes to new branch: `git checkout -b new-feature-branch`
	* remove changes from develop: `git reset --hard HEAD~2` (when two new commits has been created)
	* checks if everything it's ok: git log --oneline -5
	
## 4. When I remove file, this file is unstaged and I want to revert this file back to life

```
git reset --hard 
```		

Execute this command to bring back previously removed file (which was unstaged).	 
	
## 5. When we've got unstaged changes ("red") and want to undochanges

```
git restore some-file-name.md
git restore .
```

## 6. When there is staged file that we wana make red again
All changes will still remains in this file which truns to "red" (become unstaged)
```
git reset some_file.txt
```	
