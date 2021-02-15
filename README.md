Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO
$ cd Divo

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
$ ls
README.md

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
$ git checkout -b develop
Switched to a new branch 'develop'

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (develop)
$ git status
On branch develop
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (develop)
$ git add .

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (develop)
$ git commit -m'as'
[develop f289a96] as
 1 file changed, 2 insertions(+), 1 deletion(-)

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (develop)
$ git push origin develop
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 249 bytes | 249.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'develop' on GitHub by visiting:
remote:      https://github.com/crazze16/Divo/pull/new/develop
remote:
To https://github.com/crazze16/Divo.git
 * [new branch]      develop -> develop

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (develop)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
$ git merge develop
Updating e35c17f..f289a96
Fast-forward
 README.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/crazze16/Divo.git
   e35c17f..f289a96  main -> main

Home@DESKTOP-PVQ6CH0 MINGW64 /d/projects/DIVO/Divo (main)
