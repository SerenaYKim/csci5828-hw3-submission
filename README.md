# csci5828-hw3-submission
### Serena Kim, CU Boulder
Feb 14, 2021
###### command below


Last login: Tue Feb 16 14:00:10 on ttys000
(base) serenakim@Serenas-MacBook-Pro ~ % cd
(base) serenakim@Serenas-MacBook-Pro ~ % cd Documents
(base) serenakim@Serenas-MacBook-Pro Documents % cd GitHub
(base) serenakim@Serenas-MacBook-Pro GitHub % cd csci5828-hw3-submission
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "# csci5828-hw3-submission" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git init
Reinitialized existing Git repository in /Users/serenakim/Documents/GitHub/csci5828-hw3-submission/.git/
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "zero commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git branch -M master
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git push -u origin master
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add .idea/gitignore
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "first commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission %  echo "### Serena Kim, CU Boulder" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "second commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git log
commit a0012429dfbaee163b9af15bfdddd8e9c524ad00 (HEAD -> master)
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:04:58 2021 -0700

    second commit

commit 58df56a2e89b050b195cf41f29f0a457cb3e3c3d
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:04:34 2021 -0700

    first commit

commit 467f37bb5b0843b5168757c6b4962088a49cfc68 (origin/master)
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:04:15 2021 -0700

    zero commit
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout 467f37bb5b0843b5168757c6b4962088a49cfc68
Note: switching to '467f37bb5b0843b5168757c6b4962088a49cfc68'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 467f37b zero commit
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout -b bug-fix
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git push -u origin bug-fix
Total 0 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'bug-fix' on GitHub by visiting:
remote:      https://github.com/SerenaYKim/csci5828-hw3-submission/pull/new/bug-fix
remote:
To https://github.com/SerenaYKim/csci5828-hw3-submission.git
 * [new branch]      bug-fix -> bug-fix
Branch 'bug-fix' set up to track remote branch 'bug-fix' from 'origin'.
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "Feb 14, 2021" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "Third commit"
[bug-fix 5bc7af2] Third commit
 1 file changed, 1 insertion(+)
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo  "###### command below" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "Fourth commit"
[bug-fix e8c3ea5] Fourth commit
 1 file changed, 1 insertion(+)
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git merge master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "fifth commit conflict fixed"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "submission" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "sixth commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git log   
commit 1d1c8b1d447f90abb12dbe14d22095d4d9d3e22f (HEAD -> bug-fix)
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:08:11 2021 -0700

    sixth commit

commit b95b72b93325c6480410b75c2e3499ccde00a0cd
Merge: e8c3ea5 a001242
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:07:35 2021 -0700

    fifth commit conflict fixed

commit e8c3ea5203c5ac1f4d1488f1500d7f646f52d895
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:06:47 2021 -0700

    Fourth commit

commit 5bc7af2a9a14b425d1cf16a15cda81022da27800
Author: serena kim <serena.kim@ucdenver.edu>
Date:   Tue Feb 16 14:05:55 2021 -0700

(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission %
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout e8c3ea5203c5ac1f4d1488f1500d7f646f52d895
Note: switching to 'e8c3ea5203c5ac1f4d1488f1500d7f646f52d895'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at e8c3ea5 Fourth commit
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout -b bug-fix-experimental
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git push -u origin bug-fix-experimental
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add .idea/misc.xml
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "seventh commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "some changes" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % add README.md   
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "eight commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "#### Serena Kim, CU Boulder" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "ninth commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout master
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "more edits" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "tenth commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout bug-fix
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git merge bug-fix-experimental
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "eleventh commit conflict fixed"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % echo "command below" >> README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git add README.md
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "twelvth commit"
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git checkout master
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git merge bug-fix
(base) serenakim@Serenas-MacBook-Pro csci5828-hw3-submission % git commit -m "thirteenth merge conflict fixed"
