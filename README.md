# Git_Branching
Learning Git branching

## Define terms
 -Branch
 - 1. Isolation
 - 2. Parallel development

 ## Git Commands
 1.  Create a branch
 ```bash
     git branch "branchname"
```

2. Switching between branches
```bash
    git switch branchname
    git checkout performance
``` 

    -directly switching to a new branch

    ```bash
        git checkout -b branchname 
    ```   

3. Merging
``` bash
     git merge sourcebranch
```

4. Resolve Conflicts

```bash
    git mergetool
```

5. list all branches
`
`git branch`
`git branch -v`

`git status`

-list merged commits
 `git branch--merged`
-list unmerged commits
 `git branch --no-merged`

