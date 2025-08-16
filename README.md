![Python Tests](https://github.com/dreamer-design/ciwithfedora/actions/workflows/workflow.yaml/badge.svg)  


sample ci pipeline from fedora magazine  
[ref](https://fedoramagazine.org/python-ci-on-fedora-with-github-actions/)  


## Git commands  
### Push to remote  
git status                    which files are modified  
git add .                     stage all files, snapshot..changes need re adding  
git checkout main             cd to branch  
git commit -m "Description"   A commit is a change to files on a branch  
git push                      Push commits from local to the remote on GitHub  

### Pull to local  
git reset --hard              reset, will pull from remote  
git restore file              throw away edits, go back to last commit.  
git pull origin main          Update local main with any new changes from the remote  

git checkout -b newBranch      create a new branch that remains seperate until merged  

### Branch merge
git checkout main  
git pull origin main  
git merge feature-login  
git push origin main  
