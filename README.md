# Training

A simple training agenda to get familiar with Git
<br>
<br>

## 1. Introduction

-   Git vs. Github
-   CLI vs. GUI
    <br>

## 2. Download & Install Git

-   [https://git-scm.com/downloads](https://git-scm.com/downloads)
    <br>

## 3. Create a GitHub account

-   [https://github.com/](https://github.com/)
    <br>

## 4. VSCode’s Terminal

1. Start VSCode
2. Open New Window `ctrl + shift + n`
3. Open Terminal `ctrl + @`

### Terminal Commands

| Command  | Description                           |
| -------- | ------------------------------------- |
| $ pwd    | Show the current path                 |
| $ ls     | Lists files and directories           |
| $ cd     | Change directory                      |
| $ code . | Opens VSCode at the current directory |

<br>

## 5. Git Settings

1. Check to see if git installed properly

```
git version
```

2. Set user name and email

```
git config --global user.name "your name here"
```

```
git config --global user.email "your email"
```

### Git Commands

| Command             | Description               |
| ------------------- | ------------------------- |
| $ git remote -v     | Shows remote settings     |
| $ git config --list | Shows the config settings |

<br>

## 6. Clone a repository

### On GitHub

1. Open [https://github.com/lc-kokoku/LP](https://github.com/lc-kokoku/LP)
2. Click `Code`
3. Select `Https`
    > _SSH for advanced_
4. Click `Copy`

### In the terminal

1. Paste

```
git clone https://github.com/lc-kokoku/LP.git
```

2. Check directory

```
ls
```

3. Change directory into the main folder

```
cd LP
```

4. Open VSCode

```
code .
```

<br>

## 7. Do Git Stuff

1. Create a new branch and switch to it

```
git checkout -b this-is-my-new-branch
```

2. Make file changes
3. Check Status
```
git status
```
5. Add it to staging

```
git add .
```

5. Check Status

```
git status
```

6. Commit the change with a comment

```
git commit -m "add comments here"
```

7. Check Status

```
git status
```

8. Push branch to remote

```
git push -u origin this-is-my-new-branch
```

<br>

## 8. Pull Requests (PR)

### On GitHub

1. Click the `Compare and pull request` button
    > _Make sure your branch is selected_
2. Add some comments if you want
   <br>

## 9. Merging

-   Click merge
-   If there are any conflics, fix then merge
    <br>

## 10. Finally

1. switch back to main branch
2. pull origin main
3. delete branch or if you are gonna continue, switch to branch, then git merge origin

## References

-   https://githubtraining.github.io/training-manual/
