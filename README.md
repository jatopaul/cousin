# Web Based Billing Management System

### Main branch
Latest stable version of the application

### Master branch
Latest working code for a feature

### Individual branch
Where individual work on for developing a feature



### Basic GIT commands
git init :- Initialise the git <br>
git config user.email "you@example.com" :- To initialise the emailid for the current project <br>
git config user.name "name" :- To initialise the name for the current project <br>
git add. :- Add all the files from the root directory recursively as tracked files <br>
git remote add origin <clone_link> :- To add the github repository as the remote <br>
git fetch --all :- Fetch all the branches in the remote <br>
git branch :- List the branches present locally <br>
git branch -r :- List the branches present in the remote <br>
git checkout main :- Checks out to the main branch <br>
git merge master :- Merge the changes from the branch 'master' to the current branch <br>
git merge master --allow-unrelated-histories :- If there are no related history between the branch 'master' and the current branch <br>
git commit -m "messge" :- Commits the changes with the message "message" <br>
git ls-tree -r master --name-only :- Lists the files that are trackes in the branch "master" <br>
git push origin main :- Push the latest commited changes in the current head to the main branch <br>
git pull :- Pulls the latest changes from the repo to the current branch <br>
