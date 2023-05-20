## BUNDLE 2
# EXERCISE 1
```
PS C:\Users\student\Downloads\git_exercise> git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\student\Downloads\git_exercise> git add services.html
PS C:\Users\student\Downloads\git_exercise> git commit -m "service page added"
[ft/bundle-2 12f6c5c] service page added
 1 file changed, 12 insertions(+)
 create mode 100644 services.html
PS C:\Users\student\Downloads\git_exercise> git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\student\Downloads\git_exercise> git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 485 bytes | 161.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/Git-exercise/pull/new/ft/bundle-2
remote:
To https://github.com/AL2002MI08/Git-exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
PS C:\Users\student\Downloads\git_exercise>
```
