---
tags: [Notebooks/Github]
title: Untitles
created: '2019-09-22T04:54:25.920Z'
modified: '2019-09-22T05:48:23.407Z'
---

# Untitles

## You Need to Learn from Here
[An Intro to Git and GitHub for Beginners (Tutorial)](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

#### TODO
+ [ ] `git revert <hash code number>`
+ [ ] don't revert, just want to get a file from past.


#### basic steps
```
cd C:\Users\js\Desktop\workspace\git-learn\myproject

git init

git config --global user.email "xjs.js@outlook.com"
git config --global user.name "xjs"

touch newfile.txt
git add newfile.txt
git commit -m "This is my first commit"

```

#### branch
```
// add a new branch
git checkout -b newbranch

// look up existing branch
git branch

// switch to master branch
git checkout master

// switch back to newbranch
git checkout newbranch
```

#### remote
```
git remote add origin https://github.com/xjs-js/git-learn.git
git push -u origin master
```

#### push branch to Github
```
git push origin newbranch
```

#### PR
将分支上传到origin之后，就可以pull request。之后就可以merge，merge之后就可以删除旧的分支。本地命令行通过`git branch -d newbranch`删除；通过`git pull origin master`更新远程merger之后的内容。
