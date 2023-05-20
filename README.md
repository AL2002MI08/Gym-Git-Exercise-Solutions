## Bundle 3
# Exercise 1
```
PS C:\Users\student\Downloads\git_exercise> git add team.html
PS C:\Users\student\Downloads\git_exercise> git commit -m "created team page"
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 team.html
PS C:\Users\student\Downloads\git_exercise> git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 280 bytes | 140.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/Git-exercise/pull/new/ft/team-page
remote:
To https://github.com/AL2002MI08/Git-exercise.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.
PS C:\Users\student\Downloads\git_exercise> git checkout main
Switched to branch 'main'
PS C:\Users\student\Downloads\git_exercise> git branch ft/contact-page
PS C:\Users\student\Downloads\git_exercise> git checkout  ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\student\Downloads\git_exercise> git log
commit 1f7613361ae96e513b5531cada5fccca391df460 (HEAD -> ft/team-page, origin/ft/team-page)
Author: AL2002MI08 <alexandramizero@gmail.com>


commit f8cc145deb0b5bd4ef303bca41fe266ad47ce5dc (origin/ft/service-redesign, ft/service-redesign)
Merge: 032dbf7 6e9201c
Author: AL2002MI08 <alexandramizero@gmail.com>
Date:   Fri May 19 11:20:29 2023 +0200

    Merge branch 'main' into ft/service-redesign

commit 6e9201c37f3138caf338c22ab4b321d58b285c20 (origin/main, main, ft/contact-page)
Merge: 55debda 63b63e5

    resolved conflicts merge

Author: AL2002MI08 <alexandramizero@gmail.com>
Date:   Fri May 19 10:51:14 2023 +0200

    added list of instruction to service page

PS C:\Users\student\Downloads\git_exercise> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
PS C:\Users\student\Downloads\git_exercise> git cherry-pick 1f7613361ae96e513b5531cada5fccca391df460
 Date: Fri May 19 11:34:49 2023 +0200
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 team.html
PS C:\Users\student\Downloads\git_exercise> git add contact.html
PS C:\Users\student\Downloads\git_exercise> git commit -m "added our contact information"
[ft/contact-page 5e6b23a] added our contact information
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 contact.html
PS C:\Users\student\Downloads\git_exercise> git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

upstream, see 'push.autoSetupRemote' in 'git help config'.
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Writing objects: 100% (5/5), 491 bytes | 245.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/Git-exercise/pull/new/ft/contact-page
remote:
To https://github.com/AL2002MI08/Git-exercise.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.
PS C:\Users\student\Downloads\git_exercise> git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
PS C:\Users\student\Downloads\git_exercise> git add --all
PS C:\Users\student\Downloads\git_exercise> git commit -m "create faq page"
Revert "created team page"
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 faq.html
PS C:\Users\student\Downloads\git_exercise> git push --set-upstream origin ft/faq-page    
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 240 bytes | 240.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/Git-exercise/pull/new/ft/faq-page
remote:
To https://github.com/AL2002MI08/Git-exercise.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.
PS C:\Users\student\Downloads\git_exercise> git revert 1f7613361ae96e513b5531cada5fccca391df460
[ft/faq-page 4dd0cf9] Revert "created team page"
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 team.html
PS C:\Users\student\Downloads\git_exercise> git log
Author: AL2002MI08 <alexandramizero@gmail.com>
Date:   Fri May 19 12:16:35 2023 +0200

    Revert "created team page"

    This reverts commit 1f7613361ae96e513b5531cada5fccca391df460.

commit f4290b70b627e440dee0d8e11e2d74f68d2f5b8e (origin/ft/faq-page)
Author: AL2002MI08 <alexandramizero@gmail.com>
Date:   Fri May 19 12:14:02 2023 +0200

    create faq page

commit 5e6b23a0a403d307e5b020063b8a328c0d663928 (origin/ft/contact-page, ft/contact-page)
Author: AL2002MI08 <alexandramizero@gmail.com>
Date:   Fri May 19 12:04:07 2023 +0200

PS C:\Users\student\Downloads\git_exercise> git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 277 bytes | 138.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AL2002MI08/Git-exercise.git
   f4290b7..4dd0cf9  ft/faq-page -> ft/faq-page
PS C:\Users\student\Downloads\git_exercise>
```

