# Obtain whole commit to feature branch

First we want commit HASH from different branch, so we could get this with a help of 
following command: 

```
git log --left-right --cherry-pick --oneline current-working-feature-branch...branch-where-changes-lives
```

It prints on the terminal all unique commits for this branches, so we can get desired HASH

```
git cherry-pick 235sf346
```

And that's it! We can execute again *log* command to make sure that commits 
is no longer in output (be cause is not unique anymore)   


