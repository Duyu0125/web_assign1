# start the project
1. npm init
2. npx express-generator -e

# set up your version control
1. git
1.1 initialize the git in your local project folder
- git init

1.2 commit stage
- git add . (to track all the files)
- git commit -m "msg" (commit the current stage with message)

1.3 sync remote repo stage
- git pull origin branch_name (to sync the latest code from the github)
- git push origin branch_name (to push your current version to the github)


2. github setup
- get remote add name_of_remote_repo repo_url
    - e.g.
    ```
    git remote add origin https://github.com/....
    ```
