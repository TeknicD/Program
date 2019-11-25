Студент@A100A-02 MINGW32 /
$ git config --global --list
git config --global user.email "gzagayko@gmail.com"
git config --global core.autocrlf true
user.name=yournamel core.safecrlf true
user.email=yourname@gmail.com
core.autocrlf=true
core.safecrlf=true

Студент@A100A-02 MINGW32 /
$ git config --global user.name "TeknicD"

Студент@A100A-02 MINGW32 /
$ git config --global user.email "gzagayko@gmail.com"

Студент@A100A-02 MINGW32 /
$ git config --global core.autocrlf true

Студент@A100A-02 MINGW32 /
$ git config --global core.safecrlf true

Студент@A100A-02 MINGW32 /
$ git clone https://yourname@github.com/yourname/lazarus_mysql_simply-01
cp c:/3kurs/unit1.pas ./
ls -la
git status
git add unit1.pas
git commit -m "Hello world 31.12.2019. Add unit1.pas"
git remote add origin https://yourname@github.com/yourname/lazarus_mysql_simply-01
git remote -v
git push -u origin master
Cloning into 'lazarus_mysql_simply-01'...

remote: Repository not found.
fatal: repository 'https://github.com/yourname/lazarus_mysql_simply-01/' not found

Студент@A100A-02 MINGW32 /
$ cd lazarus_mysql_simply-01
bash: cd: lazarus_mysql_simply-01: No such file or directory

Студент@A100A-02 MINGW32 /
$ cp c:/3kurs/unit1.pas ./
cp: cannot stat 'c:/3kurs/unit1.pas': No such file or directory

Студент@A100A-02 MINGW32 /
$ ls -la
total 3088
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:51 ./
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:51 ../
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:34 bin/
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:34 cmd/
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:34 dev/
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:34 etc/
-rwxr-xr-x 1 Студент 197121  152152 ноя  6 13:21 git-bash.exe*
-rwxr-xr-x 1 Студент 197121  151640 ноя  6 13:21 git-cmd.exe*
-rw-r--r-- 1 Студент 197121   18765 ноя  4 16:14 LICENSE.txt
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:33 mingw32/
dr-xr-xr-x 9 Студент 197121       0 ноя 25 13:51 proc/
-rw-r--r-- 1 Студент 197121  156756 ноя  6 14:08 ReleaseNotes.html
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:51 tmp/
-rw-r--r-- 1 Студент 197121 1161408 ноя 25 13:34 unins000.dat
-rwxr-xr-x 1 Студент 197121 1299928 ноя 25 13:33 unins000.exe*
-rw-r--r-- 1 Студент 197121   22803 ноя 25 13:34 unins000.msg
drwxr-xr-x 1 Студент 197121       0 ноя 25 13:34 usr/

Студент@A100A-02 MINGW32 /
$ git status
fatal: not a git repository (or any of the parent directories): .git

Студент@A100A-02 MINGW32 /
$ git add unit1.pas
fatal: not a git repository (or any of the parent directories): .git

Студент@A100A-02 MINGW32 /
$ git commit -m "Hello world 31.12.2019. Add unit1.pas"
fatal: not a git repository (or any of the parent directories): .git

Студент@A100A-02 MINGW32 /
$ git remote add origin https://yourname@github.com/yourname/lazarus_mysql_simply-01
fatal: not a git repository (or any of the parent directories): .git

Студент@A100A-02 MINGW32 /
$ git remote -v
fatal: not a git repository (or any of the parent directories): .git

Студент@A100A-02 MINGW32 /
$ git push -u origin master
fatal: not a git repository (or any of the parent directories): .git

Студент@A100A-02 MINGW32 /
$

Студент@A100A-02 MINGW32 /
$ git clone https://TeknicD@github.com/TeknicD/Program
ls -la
git status
git add kod2.txt
git commit -m "Hello world 31.12.2019. Add unit1.pas"
git remote add origin https://TeknicD@github.com/TeknicD/Program
git remote -v
git push -u origin master
Cloning into 'Program'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

Студент@A100A-02 MINGW32 /
$ cd Program

Студент@A100A-02 MINGW32 /Program (master)
$ cp C:\Users\Студент\Desktop\kod2.txt
cp: missing destination file operand after 'C:UsersСтудентDesktopkod2.txt'
Try 'cp --help' for more information.

Студент@A100A-02 MINGW32 /Program (master)
$ ls -la
total 9
drwxr-xr-x 1 Студент 197121  0 ноя 25 13:54 ./
drwxr-xr-x 1 Студент 197121  0 ноя 25 13:54 ../
drwxr-xr-x 1 Студент 197121  0 ноя 25 13:54 .git/
-rw-r--r-- 1 Студент 197121 45 ноя 25 13:54 kod.txt

Студент@A100A-02 MINGW32 /Program (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Студент@A100A-02 MINGW32 /Program (master)
$ git add kod2.txt
fatal: pathspec 'kod2.txt' did not match any files

Студент@A100A-02 MINGW32 /Program (master)
$ git commit -m "Hello world 31.12.2019. Add unit1.pas"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Студент@A100A-02 MINGW32 /Program (master)
$ git remote add origin https://TeknicD@github.com/TeknicD/Program
fatal: remote origin already exists.

Студент@A100A-02 MINGW32 /Program (master)
$ git remote -v
origin  https://TeknicD@github.com/TeknicD/Program (fetch)
origin  https://TeknicD@github.com/TeknicD/Program (push)

Студент@A100A-02 MINGW32 /Program (master)
$ git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.
