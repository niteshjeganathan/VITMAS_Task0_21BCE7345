## Basic GIT Commands

##### **Code**
```
git init
```

This initiates a local repository on your system inside your current directory. 

##### Output
```
Initialized empty Git repository in /home/nitesh/demo/.git/
```
---

##### Code
```
git add * 
git add . 
git add <filename>
```

The first two lines will add all the files present in the current directory to the staging area. The third line will add the specific file to the staging area. 

---

##### Code
```
git commit -m "comment"
```

This commits everything present in your staging area with the given comment.  

##### Output
```
master (root-commit) 0ad964f] comment
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 <filename>

```
---

##### Code
```
git status
```

This outputs the current status of all the files present in the current directory. 

##### Output
```
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   staged.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	untracked.txt

```
---

##### Code
```
git log
```

This shows the recent actions made in the local repository. 

##### Output
```
commit 0ad964fdea228bb06d3b2fd2219272c16b396ad0 (HEAD -> master)
Author: Nitesh <nitesh.jeganathan2021@vitstudent.ac.in>
Date:   Wed Apr 6 17:42:38 2022 +0530

    "comment"

```
---

##### Code
```
git branch
```

This will list out all the branches present in the local repository. 

##### Output
```
*master
master2
master3
```

##### Code
```
git branch <branchName>
```

This will create a new barnch with the name "branchName". 

---

##### Code 
```
git checkout <branchName>
```

This will switch to the branch "branchName".

##### Output
```
switched to branch "branchName"
```

---

##### Code
``` 
git remote add origin <link>
```

This will add a remote server using the providing link and refer it as origin. 

---

##### Code 
```
git pull 
``` 

This will pull everything from the remote server onto your local repository. 

##### Output 
``` 
Already up to date.
```
--- 

##### Code 
``` 
git push - u origin master 
```

This will push everything from your master branch in local repository to your remote repository.

##### Output 
```
Username for 'https://github.com': niteshjeganathan
Password for 'https://niteshjeganathan@github.com': 
Counting objects: 3, done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 587 bytes | 587.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/niteshjeganathan/VITMAS_Task0_21BCE7345.git
   5c6729c..c5ddc71  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```
---
---

