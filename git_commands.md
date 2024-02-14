1. git init
   - Initializes an empty git repository
2. git checkout -b <file_name>

- Create New branch like dev and it copy all files in new branch

3. git add <file_name>

- Used to stage the untracked file

4. git add .

- Used for add all files in stage

5. git rm --cached <file>...

- for unstage means get back to untracked mode

6. git commit -m "message"

- Used to track the staged files after being added by git add

7. git --help

- Used for showing commands info

8. git clone remote url(https://github.com/afroz-ssi/Demo.git)

- clone / copy of all files from remote

9. git push origin main

- push the updated files on remote main branch

10. git config --global user.name "Username"

- for configuration of you github account
  git config --global user.email "my@gmail.com"

  11. ls -a

  - Show all files and folder

  12. git branch -M main

  - Rename of the branch like default branch (Master)

13. git push -u origin main

- if you continue push in same branch, and you don't want to write origin main again and again
  and after adding it once you can use git push only

14. git config --list

- listout the username , email that we used at the time of configurations.
