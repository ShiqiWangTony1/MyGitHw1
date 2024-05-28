shiqiwang@ShiqideMacBook-Air ~ % /opt/homebrew/bin/python /U
sers/shiqiwang/Documents/coding_temple/backend-core/week1/da
y1/python-syntax.py
Hello World
This is my First Git Hw1
shiqiwang@ShiqideMacBook-Air ~ % cd /Users/shiqiwang/Documents/coding_temple/backend-core/week1/day1
shiqiwang@ShiqideMacBook-Air day1 % git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /Users/shiqiwang/Documents/coding_temple/backend-core/week1/day1/.git/
shiqiwang@ShiqideMacBook-Air day1 % git add .
shiqiwang@ShiqideMacBook-Air day1 % git commit -m "First Git homework assignment"
[master (root-commit) b2f8940] First Git homework assignment
 1 file changed, 4 insertions(+)
 create mode 100644 python-syntax.py
shiqiwang@ShiqideMacBook-Air day1 % git remote add origin https://github.com/ShiqiWangTony1/MyGitHw1.git
shiqiwang@ShiqideMacBook-Air day1 % git branch -M main

shiqiwang@ShiqideMacBook-Air day1 % git push -u origin main

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ShiqiWangTony1/MyGitHw1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
shiqiwang@ShiqideMacBook-Air day1 % 
