# gh8274

```cmd
D:\ExtraCredit1>git init
Initialized empty Git repository in D:/ExtraCredit1/.git/

D:\ExtraCredit1>echo bin\introduction\HelloJava.class >> .gitignore

D:\ExtraCredit1>git add .

D:\ExtraCredit1>git commit -m "Initial Commit"
[master (root-commit) 978593f] Initial Commit
 8 files changed, 52 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .gitignore
 create mode 100644 .project
 create mode 100644 .settings/org.eclipse.jdt.core.prefs
 create mode 100644 bin/introduction/HelloJava.class
 create mode 100644 bin/module-info.class
 create mode 100644 src/introduction/HelloJava.java
 create mode 100644 src/module-info.java

D:\ExtraCredit1>git remote add origin https://github.com/trevortrusty/gh8274.git

D:\ExtraCredit1>git push -u origin master
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 8 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (15/15), 2.03 KiB | 1.02 MiB/s, done.
Total 15 (delta 0), reused 0 (delta 0)
To https://github.com/trevortrusty/gh8274.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

D:\ExtraCredit1>git add .

D:\ExtraCredit1>git push
Everything up-to-date
```
