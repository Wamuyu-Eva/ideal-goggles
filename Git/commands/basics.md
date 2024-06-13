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


#### Pushing to Remote Branch
```
git push  #[Pushes changes to remote branch which had been setup as the upstream branch]
git push origin [branchname]

```

####



#### Undo Last Commit without losing changes

```
git reset

git reset --soft 

git reset HEAD^ #[Resets the current branch to the most recent commit]
```

#### Undo last commit and the changes made


#### Remove Git\Uninitialize Git
```
rm -rf .git
```