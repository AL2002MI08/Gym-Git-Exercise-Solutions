## BUNDLE 3
# EXERCISE 2
```
PS C:\Users\student\Downloads\git_exercise> git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
Switched to branch 'main'
PS C:\Users\student\Downloads\git_exercise> git add home.html
PS C:\Users\student\Downloads\git_exercise> git commit -m "add div class"
On branch main
nothing to commit, working tree clean
PS C:\Users\student\Downloads\git_exercise> git status
On branch main
Changes not staged for commit:
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\student\Downloads\git_exercise> git add home.html
PS C:\Users\student\Downloads\git_exercise> git commit -m "add div class"
[main 370aee5] add div class
 1 file changed, 3 insertions(+)
PS C:\Users\student\Downloads\git_exercise> git push
To push the current branch and set the remote as upstream, use

upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\student\Downloads\git_exercise> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 396 bytes | 132.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AL2002MI08/Git-exercise.git
   6e9201c..370aee5  main -> main
PS C:\Users\student\Downloads\git_exercise> git checkout  ft/home-page-redesign  
Switched to branch 'ft/home-page-redesign'
PS C:\Users\student\Downloads\git_exercise> git fetch
PS C:\Users\student\Downloads\git_exercise> git rebase --continue
fatal: No rebase in progress?
PS C:\Users\student\Downloads\git_exercise> git push  origin ft/home-page-redesign
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (9/9), 1023 bytes | 170.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/Git-exercise/pull/new/ft/home-page-redesign
remote:
To https://github.com/AL2002MI08/Git-exercise.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
```
