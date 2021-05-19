# Cohorts
This repository keep track of the repositories of previous cohorts. 

## Housekeeping
### Add new submodule
$ git submodule add <git_repository>


### Set up submodule.recurse 
$ git config --global submodule.recurse true

### Recursively update all submodules
$ git pull --recurse-submodules

### Effectively delete submodule [Link](https://gist.github.com/myusuf3/7f645819ded92bda6677)
* $ git submodule deinit <path_to_submodule>
* $ git rm <path_to_submodule>
* $ git commit-m "Removed submodule"
* $ rm -rf .git/modules/<path_to_submodule>


### TO DO
Automatically update all submodules

