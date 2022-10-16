
# git-info


git diff --- That command compares what is in your working directory with what is in your staging area


git branch---List all of the branches in your repository


git branch <branch> ----- Create a new branch called ＜branch>


git branch -d <branch>------Delete the specified branch.

git checkout -b ＜new-branch＞----- create the new branch and immediately switch to it.

git log --oneline --graph -----to list branches in graph

--- 
## INSPECT & COMPARE


- git log:

           Show the commit history for the currently active branch. 

- git log branchB..branchA:

          Show the commits on branchA that are not on branchB.

- git diff branchB...branchA:

          Show the diff of what is in branchA that is not in branchB. 
- git show :

          Shows one or more objects (blobs, trees, tags and commits). 

- git remote add origin [url]: 
          
          Specifies the remote repository for your local repository. 
          The url points to a repository on GitHub.

git init 
initialize an existing directory as a Git repository

git clone [url]
retrieve an entire repository from a hosted location via URL

git status
show modified files in working directory, staged for your next commit

git add .
The git add command adds a change in the working directory to the staging area.

git diff
diff of what is changed but not staged

git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot





