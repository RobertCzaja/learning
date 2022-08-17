# Only when not commited 

When file is "red" and you want to revert back all changes:

	git restore somefile.txt
	
When file is already "green" you need to first make it "red":

	git reset HEAD somefile.txt
	git restore somefile.txt	
	
## When you made a commit 

> and you want to revert commtis and made changes still in your repositry available.
> For example there is 2 commits that you want to revert but you still want to keep the changes 
> in workespace as a "green" (or "red") files, so this it how it goes: 

git reset --soft HEAD~2

> So awesome! commits are gone but you still keep the changes!
> If you want to make the "green" files "red" you need to restore shits like this:

git restore --staged . 

> That's it!


 

