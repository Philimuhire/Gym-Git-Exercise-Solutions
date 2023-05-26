# The-Gym-Preparatory-Training
# This repository includes exercises in the Gym Preparatory Training.

# Bundle 1
# Exercise 1
'''Bash
USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (master)
$ git init
Initialized empty Git repository in C:/Users/USER/Desktop/GitExercises/.git/

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (master)
$ git remote

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (master)
$ git branch

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (master)
$ git stash
You do not have the initial commit yet


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 2.59 KiB | 1.29 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
   fa33ea1..151a713  main -> main

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git checkout -b dev
Switched to a new branch 'dev'

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git status
On branch dev
nothing to commit, working tree clean

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git push --set-upstream origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Philimuhire/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git checkout -b test
Switched to a new branch 'test'

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (test)
$ git status
On branch test
nothing to commit, working tree clean

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (test)
$ git push
fatal: The current branch test has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin test

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Philimuhire/Gym-Git-Exercise-Solutions/pull/new/test
remote:
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
 * [new branch]      test -> test

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (test)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git checkout -D test
error: unknown switch `D'
usage: git checkout [<options>] <branch>
   or: git checkout [<options>] [<branch>] -- <file>...

    -b <branch>           create and checkout a new branch
    -B <branch>           create/reset and checkout a branch
    -l                    create reflog for new branch
    --guess               second guess 'git checkout <no-such-branch>' (default)
    --overlay             use overlay mode (default)
    -q, --quiet           suppress progress reporting
    --recurse-submodules[=<checkout>]
                          control recursive updating of submodules
    --progress            force progress reporting
    -m, --merge           perform a 3-way merge with the new branch
    --conflict <style>    conflict style (merge, diff3, or zdiff3)
    -d, --detach          detach HEAD at named commit
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -f, --force           force checkout (throw away local modifications)
    --orphan <new-branch>
                          new unparented branch
    --overwrite-ignore    update ignored files (default)
    --ignore-other-worktrees
                          do not check if another worktree is holding the given ref
    -2, --ours            checkout our version for unmerged files
    -3, --theirs          checkout their version for unmerged files
    -p, --patch           select hunks interactively
    --ignore-skip-worktree-bits
                          do not limit pathspecs to sparse entries only
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git branch -D test
Deleted branch test (was 151a713).

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git push origin --delete test
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
 - [deleted]         test

'''

# Exercise 2

'''Bash

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html
        team.html

nothing added to commit but untracked files present (use "git add" to track)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add all
fatal: pathspec 'all' did not match any files

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add -all
error: did you mean `--all` (with two dashes)?

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add --all

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html
        new file:   team.html


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git list
git: 'list' is not a git command. See 'git --help'.

The most similar commands are
        bisect
        rev-list

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list
stash@{0}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions
  
  
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html
        team.html

nothing added to commit but untracked files present (use "git add" to track)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add home.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list
stash@{0}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add about.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add team.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list
stash@{0}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions
stash@{1}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions
stash@{2}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (b799158e43b623fd62f846610db8a9a50de672af)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list
stash@{0}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions
stash@{1}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (408d55206011ae83446287edc3c0584c3cefbbc6)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list
stash@{0}: WIP on dev: 151a713 Merge branch 'main' of https://github.com/Philimuhire/Gym-Git-Exercise-Solutions

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git add --all

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git commit -m "second commit"
[dev ddc54e5] second commit
 2 files changed, 308 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 282 bytes | 282.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
   151a713..ddc54e5  dev -> dev

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash pop
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (0b9e92487dc96e5f2d5900b804d3ca127e2decad)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git stash list

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git reset --hard
HEAD is now at ddc54e5 second commit

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$
'''
  
# Bundle 2
# Exercise 1
  
'''Bash
  
  USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git add sevices.html
fatal: pathspec 'sevices.html' did not match any files

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git add services.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git commit -m "add services.html"
[ft/bundle-2 27574d0] add services.html
 1 file changed, 154 insertions(+)
 create mode 100644 services.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 239 bytes | 23.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Philimuhire/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
'''
  
# Exercise 2
  
'''
  USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 2 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 712 bytes | 4.00 KiB/s, done.
From https://github.com/Philimuhire/Gym-Git-Exercise-Solutions
   9a546d4..0e0ce43  main       -> origin/main
Updating 151a713..0e0ce43
Fast-forward
 README.md     | 335 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 about.html    | 154 +++++++++++++++++++++++++++
 home.html     | 154 +++++++++++++++++++++++++++
 services.html | 154 +++++++++++++++++++++++++++
 4 files changed, 797 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ git add --all

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ giit status
bash: giit: command not found

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   services.html


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ git commit -m "deleted subscription feature fromservices.html"
[ft/service-redesign 41adbe6] deleted subscription feature fromservices.html
 1 file changed, 9 deletions(-)

  USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 305 bytes | 152.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0

remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Philimuhire/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git add --all

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git commit -m 'removed semibolded button'
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git add --all

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git commit -m 'removed semibolded button'
[main 2c97bad] removed semibolded button
 1 file changed, 1 insertion(+), 1 deletion(-)

USER@DESKTOP-J1GAJFD MINGW64 ~/desktop/gitexercises (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Philimuhire/Gym-Git-Exercise-Solutions.git
   0e0ce43..2c97bad  main -> main






  
  
  


