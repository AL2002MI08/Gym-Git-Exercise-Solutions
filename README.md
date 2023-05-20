##Bundle 4 
# Exercise 2
```bash
PS C:\Users\student\Downloads\git_copy> git checkout -b ft/footer
Switched to a new branch 'ft/footer'
PS C:\Users\student\Downloads\git_copy> git add .
PS C:\Users\student\Downloads\git_copy> git commit -m "added content page"
[ft/footer 15d39b3] added content page
 1 file changed, 9 insertions(+)
 create mode 100644 content.html
PS C:\Users\student\Downloads\git_copy> git add . 
[ft/footer 0e3a4b4] added new changes to content page
 1 file changed, 1 insertion(+)
PS C:\Users\student\Downloads\git_copy> git push ft/footer
fatal: 'ft/footer' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\student\Downloads\git_copy> git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\student\Downloads\git_copy> git push origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 774 bytes | 18.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote: 
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/Gym-Git-Exercise-Solutions/pull/new/ft/footer
remote:
To https://github.com/AL2002MI08/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/footer -> ft/footer
```
