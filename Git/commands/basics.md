### Git Basics
#### Initializing Git Repository
```
git init   #[Creates a folder called .git which has all information that is required for version control. It has these files :hooks,info,logs,objects and refs, the following files HEAD, index, description and config]
```

#### Adding remote origin

```
git remote add origin [url]
```

#### Adding Changes to Git

```
git add  .    #[All changes]
git add /path/to/add   #[Specific files and directories]
```
#### Commiting Changes

```
git commit -m "message of the commit"    

git commit   #[If you have set up git to open your editor, you add the edit message from the editor]
```

#### Setting Up A Branch For Upstream

```
git push -u origin [name of the branch]  #Method 1

git push --set-upstream origin [name of the branch]  #Method 2
```
#### Pushing to Remote Branch
```
git push  #[Pushes changes to remote branch which had been setup as the upstream branch]
git push origin [branchname]

```

#### Check files that have been affected/staged
```
git status
```
#### Undo Last Commit without losing changes

```
git reset

git reset --soft 

git reset HEAD^ #[Resets the current branch to the most recent commit]
```

#### Undo last commit and the changes made
```
git reset --hard HEAD~1

```
#### Undo last commit that has not been pushed

```
git reset --soft HEAD~
git reset --soft HEAD^
```

#### Undo A Specific Commit

```
git revert [commit ID] --no-edit #[In this case no commit message is needed and a new commit is made which is a reverse of the one with that id]
```

### Modify commit message 

```
git commit --amend   #[In this case, the last commit message is forgotten and assumed to not have existed in the first place]
```

#### Remove Git\Uninitialize Git
```
rm -rf .git
```