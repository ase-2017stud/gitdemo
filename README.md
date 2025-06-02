# Git Collaboration Basics

## Important Terms

- Repository
- Working Tree
- Staging Area
- Branches
- Remote 
- Index

Before anything else is said:

`git <command> --help` (and a good LLM) is your friend


## Multiple Developers

* Collaborate using one branch, multiple developers
* Central repo in GitHub, local repos at developers' machines

### Get Changes from remote
1.`git status` and `git diff` and `git log` -> see if all is ready
2. `git pull`
  1. No problems: automatic merge or no changes -> continue with do local changes
  2. Merge problems: automatic merge files for some files and locations  -> resolve conflicts before continuing
	
### Do changes
1. <do changes> in editor
2. See changes: `git status` and `git diff`
3. Repeat 1. and 2.
4. Prepare changes, prevent loss of changes: `git add <files>`
5. Repeat 1. - 4.
6. Make commit in local repository from changes: `git commit`
7. Repeat 1. - 6.
8. "Publish" aka push your work to remote repo: `git push`


Useful tools:
(git diff)

(git checkout/revert/branch)
