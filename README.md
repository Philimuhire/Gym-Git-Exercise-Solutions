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



  
  
  


