# Github Commands 
## Initialize git 
```
git init
```

## Adding things to git 
```
git add . # Adds all changes to git
```
```
git add README.md # adds certain files to git 
```
## Checking git status 
```
git status # checks which files git is currently looking at 
```
## Commiting things to git 
```
git add . # Making a save state 
git commit -am "Initial commit" # Adds all files that are in staging 
```
## Make a branch 
``` 
git branch # Displays all branches of git 
git branch mark1 # Creates a new branch 
```
## Work on new branch 
```
git checkout mark1 # Switches to the specific branch 
``` 
## Merging branches 
```
git checkout master # Move to the branch that you want to merge another branch to 
git merge mark1 # Merges branch to current git branch
```
## Pushing to github with SSH
```
git remote add origin git@github.com:KCYL/testing.git # On the remote repo add the origin set as git@github.com:KCYL/testing.git
git remote -v # checks the link (SSH or HTTPS)
git push -u origin master # Pushes the commits to github 
```
## Pushing branches to github 
```
git push -u origin mark2 # Pushes specific branch to online repo
# From the online repo you merge the branch with the master by creating a pull merge request 
```

## Pulling changes from github 
```
git pull --rebase # Pulls all changes from the online repo, the rebase puts your most recent push on top of the changes (Just in case there are multiple pushing code)
```
