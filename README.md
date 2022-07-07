# Follow the below steps to make a local repo to github repo

demo for local directory and then pushing to github

Initializing a repository locally and then pushing it to a remote location like github.

## subheader

Turning local directory into git repo:

Create a new drectory with a README file and save changes then write the following commands

1. git init
2. git status
3. git add .
4. git commit
5. make a new repo on github and copy the link
6. git remote add origin https://github.com/ajirk/demo_repo.git
7. git remote -v: shows the repositories connected to this repo
8. git push origin master
   to push into origin master by default : git push -u origin master

## Branching in github

Well this is all happening in one branch and that is the master branch
Now we will look at branches
There are different branches like master, feature, hot fix(for fixing bugs), etc

1. to know what branches we have in our repo:
   git branch
   (the star beside the branch name shows the current branch we're in)
2. to create new branch and swtiching to it simulataneously:
   git checkout -b feature-readme-branching
3. to change branch
   git checkout

<!-- <<<<<<< HEAD -->

make a branch, make code changes, pull request, delete the feature branch

### reset/undo commits

to go back to previous commits or unstage the commit

git reset (to go the last commit)

git reset HEAD~1 (HEAD points to the last commit~ here we want to go 1 commit further than the head)

### Fork

# Allows to make changes anywhere

## Pull requests

A pull request is a request to pull your code into another branch.
if we want our code to be pulled into master branch: we make a pr from the feature branch to the master branch
Once the pr is merged,generally the feature branch is deleted and switch back to the master branch.
For making further code changes, we'll have to start a new branch.

so in all:
make commits
make pr
then merge (forever!)

<!-- > > > > > > > a17a01a6dd066ff17404dc177fd00aef15ea131b -->
