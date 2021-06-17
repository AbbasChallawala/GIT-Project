C:\Users\abbas.challawala>cd C:\Users\abbas.challawala\source\repos\AbbasChallawala

C:\Users\abbas.challawala\source\repos\AbbasChallawala>mkdir GIT

C:\Users\abbas.challawala\source\repos\AbbasChallawala>cd GIT

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git init
Initialized empty Git repository in C:/Users/abbas.challawala/source/repos/AbbasChallawala/GIT/.git/

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>echo this is new file > readme.txt

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git add .

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git commit -m "commit"
[master (root-commit) 363df43] commit
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git status
On branch master
nothing to commit, working tree clean

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git remote add origin https://github.com/AbbasChallawala/GIT-Project.git

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>git status
On branch master
nothing to commit, working tree clean

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT>cd ..\

C:\Users\abbas.challawala\source\repos\AbbasChallawala>cd GIT-Project

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT-Project>git fetch origin

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT-Project>git checkout -b development origin/development
fatal: A branch named 'development' already exists.

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT-Project>git merge main
Merge made by the 'recursive' strategy.
 .vs/GIT-Project/v16/.suo | Bin 0 -> 3584 bytes
 abbas.html               |   5 +++++
 2 files changed, 5 insertions(+)
 create mode 100644 .vs/GIT-Project/v16/.suo

C:\Users\abbas.challawala\source\repos\AbbasChallawala\GIT-Project>

Hello this my Git Assignment commands