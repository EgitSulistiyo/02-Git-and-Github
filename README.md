# 02-Git-and-Github
DPRD  KSB@DEWAN MINGW64 ~/Git dan Github
$ mkdir git-basic

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github
$ cd git-basic

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic
$ touch first.txt

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic
$ git init
Initialized empty Git repository in C:/Users/DPRD  KSB/Git dan Github/git-basic/.git/

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git add .

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git commit -m "adding first.txt"
[master (root-commit) 7c89ea4] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ touch second.txt

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git add .

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git commit -m "adding second.txt"
[master f4ed9df] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ rm first.txt

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git add .

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git commit -m "removing first.txt"
[master f2c65f3] removing first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt

DPRD  KSB@DEWAN MINGW64 ~/Git dan Github/git-basic (master)
$ git log
commit f2c65f3f02695fdcd99507bfa231f8302e0522a9 (HEAD -> master)
Author: Egit Sulistiyo Bahri <bang.eg60@gmail.com>
Date:   Sat Mar 5 11:03:28 2022 +0700

    removing first.txt

commit f4ed9dfa665177fce000071551d531ee90476573
Author: Egit Sulistiyo Bahri <bang.eg60@gmail.com>
Date:   Sat Mar 5 11:00:44 2022 +0700

    adding second.txt

commit 7c89ea4c5d9aff2fd52e3f351a74f6b1de77d8b3
Author: Egit Sulistiyo Bahri <bang.eg60@gmail.com>
Date:   Sat Mar 5 10:58:38 2022 +0700

    adding first.txt
