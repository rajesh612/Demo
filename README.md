# Demo
github demo
## To clone a Repository
        git clone git@github.com:rajesh612/Demo.git
## To Push back to repo
        git status
        git add .
        git commit -m "first commit"
        git push -u origin master / HEAD(present branch) / branch name

## To create a new branch
     git checkout -b rajesh(branch name)
  
## To get all branches
        git checkout
  
## To redirect to a branch
        git checkout rajesh(branch)
  
## To pull from master repo
        git pull origin master
        
## To squash merge
        git rebase -i HEAD~# of commits
  
## To add upstream for fork branches
      git remote -v
      git remote add upstream git@github.com:rajesh612/Demo.git

## To update forked branch with upstream branch
      git clean -df
      git reset --hard upstream/branch
      git pull upstream branch
      git push origin branch --force
