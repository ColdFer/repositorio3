"# repositorio3" 
C:\Users\ferna\disweb\repositorio2>cd ..

C:\Users\ferna\disweb>mkdir repositorio3

C:\Users\ferna\disweb>cd repositorio3

C:\Users\ferna\disweb\repositorio3>echo "# repositorio3" >> README.md

C:\Users\ferna\disweb\repositorio3>git init
Initialized empty Git repository in C:/Users/ferna/disweb/repositorio3/.git/

C:\Users\ferna\disweb\repositorio3>git add README.md

C:\Users\ferna\disweb\repositorio3>git commit -m "primer commit"
[master (root-commit) 6ecfeb2] primer commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\ferna\disweb\repositorio3>git branch -M main

C:\Users\ferna\disweb\repositorio3>git remote add origin https://github.com/ColdFer/repositorio3.git

C:\Users\ferna\disweb\repositorio3>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 230 bytes | 230.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ColdFer/repositorio3.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\ferna\disweb\repositorio3>code .

C:\Users\ferna\disweb\repositorio3>