  ### Basic Workflow 
  ### Branching Workflow
  ### Merging Workflow
  ### Rebasing
  ### Remote Integration
  ### Git Clone
  ### ABAP git local repo demo and then push to remote
  ### ABAP git clone remote repo




### Basic Workflow 

```CMD
git config --global receive.denyCurrentBranch updateIns
tead
git --version
git init
git clone
git status
git add 
git commit
git push
git diff
git diff --staged
git log
git diff <commit1> <commit2>  "Compare with last commit"
```

### Branching Workflow

```CMD
git branch <branch name>
git checkout change_alice
git rev-parse HEAD " find where we are"
git branch
git branch -a " to see all remote branches"
```
### Merging Workflow

```
git checkout master
git merge <branch name>
```

### Rebasing

``` 
git rebase master " do in the branch"
```

### Remote Environment update

``` 
git fetch
git pull
git stash " put the current layer on somewhere else
git stash pop "apply back
git stash apply 
git stash list
git stash show

```
## Useful Resources

- [Free Git book](https://git-scm.com/book/en/v2)
- https://jwiegley.github.io/git-from-the-bottom-up/
