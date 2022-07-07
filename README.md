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
