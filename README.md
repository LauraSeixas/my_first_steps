Todas as repostas do exercício
https://github.com/LauraSeixas/my_first_steps.git

lauri@lauraseixas MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/lauri/.git/
lauri@lauraseixas MINGW64 ~ (master)
$ mkdir my_first_steps
lauri@lauraseixas MINGW64 ~ (master)
$ cd my_first_steps
lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ git remote add origin https://github.com/LauraSeixas/my_first_steps.git
lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ git remote -v
origin  https://github.com/LauraSeixas/my_first_steps.git (fetch)
origin  https://github.com/LauraSeixas/my_first_steps.git (push)

lauri@lauraseixas MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/lauri/.git/

lauri@lauraseixas MINGW64 ~ (master)
$ git add ola_mundo2.txt

lauri@lauraseixas MINGW64 ~ (master)
$ git commit -m "primeiro commit"
[master 9c94fef] primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo2.txt

lauri@lauraseixas MINGW64 ~ (master)
$ git remote add origin git@github.com:LauraSeixas/my_first_steps.git
error: remote origin already exists.

lauri@lauraseixas MINGW64 ~ (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 488 bytes | 488.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LauraSeixas/my_first_steps.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
lauri@lauraseixas MINGW64 ~ (master)
$ git remote show origin
* remote origin
  Fetch URL: https://github.com/LauraSeixas/my_first_steps.git
  Push  URL: https://github.com/LauraSeixas/my_first_steps.git
  HEAD branch: master
  Remote branch:
    master tracked
  Local branch configured for 'git pull':
    master merges with remote master
  Local ref configured for 'git push':
    master pushes to master (up to date)

lauri@lauraseixas MINGW64 ~ (master)
$ cd my_first_steps/

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ mkdir serei_ignorado.txt

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ touch .gitignore

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ nano serei_ignorado.txt

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ ls
ola_mundo.txt  serei_ignorado.txt

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ pwd
/c/Users/lauri/my_first_steps

lauri@lauraseixas MINGW64 ~/my_first_steps
$ git init
Initialized empty Git repository in C:/Users/lauri/my_first_steps/.git/

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ git add .
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   ola_mundo.txt

lauri@lauraseixas MINGW64 ~/my_first_steps (master)
$ git commit -m "gitignore"
[master (root-commit) 89b99b3] gitignore
 2 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 ola_mundo.txt
lauri@lauraseixas MINGW64 ~/my_first_steps (master)

$ git status
On branch master
nothing to commit, working tree clean
