This is Salman Thasleem's first git project!

---Git CheatSheet---


    Commands related to a remote repository:
        git clone git@github.com:USER-NAME/REPOSITORY-NAME.git or git clone https://github.com/user-name/repository-name.git
        git push origin main
    Commands related to workflow:
        git add .
        git commit -m "A message describing what you have done to make this snapshot different"
    Commands related to checking status or log history
        git status
        git log

The basic Git syntax is program | action | destination.

For example,

    git add . is read as git | add | ., where the period represents everything in the current directory;
    git commit -m "message" is read as git | commit -m | "message"; and
    git status is read as git | status | (no destination).

## check branches
```
git branch
```
## switch between branches
```
git checkout 
```
## create branch
```
git checkout -b name_of_the_branch
```
## check changes made
```
git diff branch_name
```
## push branch upstream 
```
git push -u origin branch_name
```
## make PR

## get changes to the local branch
```
git pull origin master
```
```
git pull
```
## delete branch
```
git branch -d branch_name
```
## for modified files
```
git commit -am ""
```
Some Changes

