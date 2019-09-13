# GitHub-dokumetacia

1. `git status`  - dáva informáciu, kde sa nachádzam vrámci stromu historie, dáva informáciu o aktualnom stave vyklonovaného repozitára.<br>
Môj bash
```
gitst="git status"
```

2. `git add -A` - z unstaged files sa vsetky subory, teda "-all" presunu/pridaju do staged files
```
gitaa="git add -A ."
```

3. `git reset` -  zmazanie jedneho nepusnuteho commitu.
```
gitrh="git reset --hard HEAD^${1}" 
``` 

4. `git checkout -` - 
```
gitco-="git checkout -"
```
5.

```
gitco="git checkout"
```
6. `git checkout -b` - tento prikaz musi obsahovat nazov brage, ktory idem vyrobit.

```
gitcob="git checkout -b"
```




```
gitcp="git cherry-pick" # -> git pu
```




```
gitcm="git commit -m"
```


```
gitcf="git commit --fixup ${1}" # git rebiad -> git ca -> git puf
```


```
gitca="git commit --amend --no-edit"
```


```
gitrsh="git reset --soft HEAD~${1}" # merge pushed commits, after use ->`git cm "message"` -> `git 
```

puf`
```
gitcam="git commit --amend -m"
```


```
gitrlcnp="git reset HEAD~1" # if you not pushed commit on branch and you want back
```




```
gitpu="git push"
```


```
gitpuf="git push -f"
```


```
gitpus="git push -u origin HEAD"
```




```
gitstl="git stash list"
```


```
gitstm="git stash save"
```


```
gitstd="git stash drop"
```


```
gitstp="git stash pop"
```



****
```
gitm="git merge"
```




```
gitrebi="git rebase -i"
```


```
gitrebc="git rebase --continue"
```


```
gitrebs="git rebase --skip"
```


```
gitrebt="git rebase --edit-todo"
```


```
gitrebiad="git rebase -i --autosquash develop"
```


#-------------- special
```
gitrw="git aa && gca && gpuf"
```


#-------------- lost commit
```
gitfh1="git fsck --lost-found"
```


```
gitfh2="git reflog"
```


