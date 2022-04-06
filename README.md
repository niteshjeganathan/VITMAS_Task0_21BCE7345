## Basic GIT Commands

##### Code
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

First two lines of the code will add everything to the staging area that is present in your current directory. 
The third line will add the specific file to the staging area. 
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
