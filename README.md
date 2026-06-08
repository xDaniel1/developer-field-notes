# Developer Field Notes

A personal reference site for Git commands, habits, and reminders built during bootcamp.

## Live site
[View on GitHub Pages](https://yourusername.github.io/developer-field-notes)

## Features
- Explanation of Git vs GitHub
- Daily edit → stage → commit → push loop
- Quick reference for 8+ Git commands
- What not to commit and why

## One thing I learned
Staging is a separate step from committing. Git doesn't automatically include every changed file — you choose what goes into each snapshot.

## Git Practice Evidence
developer-field-notes git:(feature/improve-responsive-styling) git checkout main
git pull origin main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 926 bytes | 926.00 KiB/s, done.
From https://github.com/xDaniel1/developer-field-notes
 * branch            main       -> FETCH_HEAD
   000724c..f642670  main       -> origin/main
Updating 000724c..f642670
Fast-forward
 styles.css | 30 ++++++++++++------------------
 1 file changed, 12 insertions(+), 18 deletions(-)
➜  developer-field-notes git:(main) git log --oneline
git log --oneline --graph --all
git branch --all
➜  developer-field-notes git:(main) ✗ git log --oneline --graph --all

[9]  + 86479 suspended  git log --oneline --graph --all
➜  developer-field-notes git:(main) ✗ git log --oneline --graph --all
➜  developer-field-notes git:(main) ✗ ### git branch --all
➜  developer-field-notes git:(main) ✗ git add README.md
git commit -m "Add git practice evidence to README"
git push origin main
[main d9f8a2b] Add git practice evidence to README
 1 file changed, 4 insertions(+), 1 deletion(-)
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 10 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 420 bytes | 420.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/xDaniel1/developer-field-notes.git
   f642670..d9f8a2b  main -> main


## Git Practice Evidence

### git log --oneline

## Live Site
[View deployed site](https://xdaniel1.github.io/developer-field-notes)