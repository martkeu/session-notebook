# Git

## Basic Operations
```
git switch -c <branch>      create a new branch and switch to it
git branch -d <branch>	    delete a branch
git switch <branch>	        switch branches
git branch	                list your branches
git branch -a	            list all branches (local and remote)
```

## Basic Workflow for a pull request

- Create a new branch with git switch -c <branchname>.
- Make changes to the code / write your code fpr the feature.
- Push the changes and the new branch with git push -u origin <branchname> (after you have done this once you can use git push for this branch)
- Create a pull request on GitHub from the new branch into main
- Share the pull request with your team
- Review the pull request, implement changes if needed, push again to update the pull request until it gets approved
- Merge the pull request into main
- Don't forget to git pull inside the main branch on your local machine
- Delete the new branch on GitHub and locally