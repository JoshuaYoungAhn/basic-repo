# basic-repo
Assignment in Git Tracks
josht@DESKTOP-HKBONT8 MINGW64 ~
$ cd desktop

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop
$ mkdir basic repo

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop
$ cd basic repo
bash: cd: basic: No such file or directory

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop
$ cd "basic repo"

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo
$ ls
colorpicker.html  hoverin.zip  'Josh Ahn EXAM.zip'  sorting_images/

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo
$ git add .
fatal: Not a git repository (or any of the parent directories): .git

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo
$ git init
Initialized empty Git repository in C:/Users/josht/Desktop/basic repo/.git/

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo (master)
$ git add .

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo (master)
$ git commit -m "Uploading Bootcamp Content"
[master (root-commit) 6486a7c] Uploading Bootcamp Content
 Committer: Swift Snow <Swift Snow>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 11 files changed, 115 insertions(+)
 create mode 100644 Josh Ahn EXAM.zip
 create mode 100644 colorpicker.html
 create mode 100644 hoverin.zip
 create mode 100644 sorting_images/ninja.png
 create mode 100644 sorting_images/sort1.png
 create mode 100644 sorting_images/sort2.png
 create mode 100644 sorting_images/sort3.png
 create mode 100644 sorting_images/sort4.png
 create mode 100644 sorting_images/sort5.png
 create mode 100644 sorting_images/sortableninja.html
 create mode 100644 sorting_images/sortninja.css

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo (master)
$ git remote add origin https://github.com/SpeedClick/basic-repo.git

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo (master)
$ git push -u origin master
Counting objects: 14, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (14/14), done.
Writing objects: 100% (14/14), 476.87 KiB | 0 bytes/s, done.
Total 14 (delta 0), reused 0 (delta 0)
To https://github.com/SpeedClick/basic-repo.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

josht@DESKTOP-HKBONT8 MINGW64 ~/desktop/basic repo (master)
