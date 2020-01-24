 This is a README.md created from the 3-way-merge exercise \n

 What does git log --oneline --graph --all is
 \* 021a493 (HEAD -> master) Added readme
 | * 97246a6 (greeting) Added greeting
 |/
 \* f66c1f3 (origin/master, origin/HEAD) Fresh start
 \*   0b4bcbc Merge branch 'greeting'
 |\
 | * 5d47aec Added greeting.txt
 \* | 018d7db Changed the readme
 |/
 \* 7430f6f First
 \* 91eda5e Initial commit

 What does git log look like? \n
 commit 46d1fcb55db56ba11054e4b5aa98c5a290ac1d64 (HEAD -> basic-commits, origin/master, origin/HEAD, master) \n
 Merge: 021a493 97246a6 \n
 Author: apagsibi <apagsibi@uci.edu> \n
 Date:   Fri Jan 24 02:30:02 2020 -0800 \n

    Merge branch 'greeting'

 commit 021a493988e77c5866ad65a52c943e4c1aec7469
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Fri Jan 24 02:27:39 2020 -0800

    Added readme

 commit 97246a63ee9901042d4b19801abbf29391f3b0c9 (greeting)
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Fri Jan 24 02:25:31 2020 -0800

    Added greeting

 commit f66c1f3e59932b442dfb81a6fb187d5182e4e32b
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Fri Jan 24 02:22:25 2020 -0800

     Fresh start

 commit 0b4bcbc5960a64388a244755962616eb4dcad2df
 Merge: 018d7db 5d47aec
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Thu Jan 23 19:34:40 2020 -0800

     Merge branch 'greeting'

 commit 018d7dbdc60223dee864d810faa2ac764ef2534a
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Thu Jan 23 19:33:04 2020 -0800

     Changed the readme

 commit 5d47aec3852f19bc3a1649ee1ac258942c2eb016
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Thu Jan 23 19:31:30 2020 -0800

    Added greeting.txt

 commit 7430f6f58e54761638e7a207383647875b2f073e
 Author: apagsibi <apagsibi@uci.edu>
 Date:   Thu Jan 23 19:29:28 2020 -0800

     First

 commit 91eda5eaee3e5cf26dd8a54514ed005bd7bde05c
 Author: AllenMNP <33591865+AllenMNP@users.noreply.github.com>
 Date:   Thu Jan 23 19:06:56 2020 -0800

     Initial commit

 What does the output from git status look like now after creating a new file?
 On branch basic-commits
 Untracked files:
   (use "git add <file>..." to include in what will be committed)
         basic-commits/

 nothing added to commit but untracked files present (use "git add" to track)

 What does git status look like after adding the file to the staging area?
 On branch basic-commits
 Changes to be committed:
   (use "git restore --staged <file>..." to unstage)
         new file:   basic-commits/newfile.txt

 What does git status look like after commiting the content in staging?
 On branch basic-commits
 nothing to commit, working tree clean

 What does git status look like after changing the content?
 On branch basic-commits
 Changes not staged for commit:
   (use "git add <file>..." to update what will be committed)
   (use "git restore <file>..." to discard changes in working directory)
         modified:   basic-commits/newfile.txt

 no changes added to commit (use "git add" and/or "git commit -a")

 What does git status look like after adding the file to the staging area after it was changed?
 On branch basic-commits
 Changes to be committed:
   (use "git restore --staged <file>..." to unstage)
         modified:   basic-commits/newfile.txt

 What does git status look like after committing the last change?
 On branch basic-commits
 Changes not staged for commit:
   (use "git add <file>..." to update what will be committed)
   (use "git restore <file>..." to discard changes in working directory)
         modified:   basic-commits/newfile.txt

 no changes added to commit (use "git add" and/or "git commit -a")
