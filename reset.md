git reset --hard HEAD~ 
remove only last commit

git reset some_file.txt
git reset -- some_file.txt
	When you decide to revet "add" command 
	File become "red" again and changes in will remain	
	
git reset 
	all files becomes "red" from "green"
----------------------------------------------------
📌 We have 2 commints on the branch, then we execute:

git reset --soft HEAD~2

result will be following: commits will be removed but changes will remains
in "red" files. When we not specified option --soft/--hard by default is soft. 
When we used --hard then commits will be removes as well as any changes. Branch
will be absolutely clear.
----------------------------------------------------

git reset --hard 345f   | there is no changes at all
git reset --soft 345f   | changes remains as "green"
git reset 345f          | changes remains as "red"
