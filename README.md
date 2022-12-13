# Training

*references
- https://githubtraining.github.io/training-manual/



## 1. Introduction
- Git vs. Github
- CLI vs. GUI



## 2. Download & Install Git
- [https://git-scm.com/downloads](https://git-scm.com/downloads)



## 3. Create a GitHub account
- [https://github.com/](https://github.com/)



## 4. VSCode’s Terminal

1. Start VSCode
2. Open New Window
`ctrl + shift + n`
3. Open Terminal
`ctrl + @`

### Terminal Commands
* $ pwd
* $ ls 
* $ cd
* $ code .



## 5. Git Settings
1. Check to see if git installed properly
```
git version
```
2. Set user name and email
```
git config —global user.name “”
git config —global user.email “”
```
### Git Commands
* $ git remote -v
* $ git config —list



## 6. Clone a repository

1. Open [https://github.com/lc-kokoku/LP](https://github.com/lc-kokoku/LP)
2. Click `Code`
3. Select `Https` (SSH for advanced)
4. Click `Copy`

in the terminal
1. Type
    * $ git clone https://github.com/lc-kokoku/LP.git
2. Check directory
    * $ ls
3. $ Change directory into the main folder
    * $ cd LP
4. Open VSCode
    * $ code .



## 7. Do Git Stuff
1. Create a new branch and switch to it
    * $ git checkout -b new-branch
2. Make file changes
3. Add it to staging
    * $ git add .
4. Check Status
    * $ git status
5. Commit the change with comment
    * $ git commit -m “”
6. Check Status
    * $ git status
7. Push branch to remote
    * $ git push -u origin new-branch (-u only for first time)



## 8. Pull Requests (PR)
On GitHub
1. 


