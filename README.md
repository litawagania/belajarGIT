Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (main)
$ git branch Tugas-git

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git add Tugas-git.txt

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git config --global user.email "carmelitawagania0110@gmail.com"

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git config --global user.name "litawws"

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 778cfaf] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (main)
$ git merge Tugas-git
Updating a7c9b0c..778cfaf
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

HP@LAPTOP-12TDJ5GH MINGW64 /c/GIT/belajarGit (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 286 bytes | 95.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/litawagania/belajarGIT.git
   a7c9b0c..778cfaf  main -> main
