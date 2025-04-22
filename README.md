# LL
hi
![clone command](./f1.png)
```bash
git add .
git commit -m "figure 1"
git push
```

![add,push,commit](./f2.png)

`git status`
![status](./f3.png)

> Final step done

![diff](./f4.png)

> Checking the block code 

# LAB-2 GIT COMMANDS
*BRANCHING*


Create a file and do 3 commits in it
1st change
```bash
git add .
git commit -m "version1"
```
2nd change
```bash
git add .
git commit -m "version2"
```

3rd change
```bash
git add .
git commit -m "hello3"
```



View all commits by using git log

```bash
git log
```

![allcommit](./f5.png)

```bash
git branch featur1
git log
```


![allcommit](./f6.png)

CREATE NEW FILE AND ADD TWO COMMITS
```bash
git add.
git commit -m "feature commit 1"
```
```bash
git add.
git commit -m "feature commit 2"
```



![allcommit](./f7.png)


```bash
git checkout main
git log
```


![allcommit](./f8.png)


#Merging
```bash
git checkout feature1
git log

```

![allcommit](./f9.png)

Do the comit 3 in feature branch
```bash
git add .
git commit -m "feature done"
git log

```

![allcommit](./f10.png)

switching to master branch and perform merging
```bash
git checkout main
git merge feature1 -m "Merging featutre 1"
git log

```
open integrated terminal of MAIN repo
```bash
git submodule add https://github.com/SAGAR-SINGH-X-CUBE/JS.git css
git submodule add https://github.com/SAGAR-SINGH-X-CUBE/CSS.git css
git add .
git commit -m "submodule added"
git push

```
![allcommit](./f12.png)

