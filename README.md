# git basics

- `git init`: initialize git repository in current working directory
- `git status`: gives status
- `git add <FILE>`: adds <FILE> to staging area
- `git commit`: creates a commit, you provide message

- `git log` : shows you the log of your commit
    - `git log --oneline`: shows one line of log

- `HEAD`: where you currently are (the version of files on computer)
- `git diff HEAD~<NUM> <FILE>`: compares current file to file <NUM> ago
    - `git diff <HASH> <FILE>`: compares current file to <HASH> version 

- Use `git status` to help you find the commands to unstage or restore file
- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH>
    - if you run `git checkout <HASH>` without  <FILE> 
    - You can fix this running `git checkout main`
 
- git ignores empty folders
- use `.gitkeep` to "keep" an empty folder
- use `.gitignore` to ignore files/patterns
    
# remotes

- `ssh-keygen`: to create ssh keys
- `git remote add <URL>`: adds the URL
- `git push origin main`: push main branch to origin remote
