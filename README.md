# Web Based Billing Management System

### Main branch
Latest stable version of the application

### Master branch
Latest working code for a feature

### Individual branch
Where individual work on for developing a feature



### Basic GIT commands
git init :- Initialise the git
git config user.email "you@example.com" :- To initialise the emailid for the current project
git config user.name "name" :- To initialise the name for the current project
git add. :- Add all the files from the root directory recursively as tracked files
git remote add origin <clone_link> :- To add the github repository as the remote
git fetch --all :- Fetch all the branches in the remote
git branch :- List the branches present locally
git branch -r :- List the branches present in the remote
git checkout main :- Checks out to the main branch
git merge master :- Merge the changes from the branch 'master' to the current branch
git merge master --allow-unrelated-histories :- If there are no related history between the branch 'master' and the current branch
git commit -m "messge" :- Commits the changes with the message "message"
git ls-tree -r master --name-only :- Lists the files that are trackes in the branch "master"
git push origin main :- Push the latest commited changes in the current head to the main branch
git pull :- Pulls the latest changes from the repo to the current branch
