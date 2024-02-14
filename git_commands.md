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
- ---------------- BRANCH COMMANDS --------------
15. git branch 
- To check in which branch we are currently.
16. git branch -M main 
- To rename default branch master to main
17. git checkout <branch_name>
- To navigate branch means switch to branch
19. git checkout -b <branch_name>
- To create new branch
20. git branch -d <branch_name>
- To delete the branch
- ---------------- BRANCH MERGING COMMANDS --------------
21. git diff <branch_name>
- To compares commits, branches, files and more.
22. git merger <branch_name>
- To merger 2 branches
23. Way-2 PR(Pull Request) by GUI
- ----------------  PULL COMMANDS --------------
24. git pull origin main 
- Used to fetch and download content from a remote app and immediately update the local repo to match that content.

25. We can add others command here 

111. or create a new repository on the command line
echo "# git_commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/afroz-ssi/git_commands.git
git push -u origin main
122. …or push an existing repository from the command line
git remote add origin https://github.com/afroz-ssi/git_commands.git
git branch -M main
git push -u origin main
