# Demonstration Project for SEP
This is a demonstration project for the Software Engineering Project 2025 git session 
It is a nice day to do this


# Git Collaboration Basics

## Important Terms

- Repository
- Working Tree
- Staging Area
- Index
- Branches
- Remote

Before anything else is said:

`git <command> --help` (and a good LLM) is your friend

## Single Developer

Base workflow, Single branch, Local + Remote Repo

### Preparation (not need if clone from remote repo/GitHub)

* Connect local to remote repo via name <remotename> `git remote add <remotename> <GitHub repo url>`

### Do changes
1. <do changes> in editor
2. See changes: `git status` and `git diff`
3. Repeat 1. and 2.
4. Prepare changes, prevent loss of changes: `git add <files>`
5. Repeat 1. - 4.
6. Make commit in local repository from changes: `git commit`
7. Repeat 1. - 6.
8. "Publish" aka push your work to remote repo: `git push`
