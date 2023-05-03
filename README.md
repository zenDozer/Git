# Git commands

***1. Git configuration - user name***

`git config --global user.name zenDozer`

***2. Git configuration - e-mail***

`git config --global user.email zenAlexM@gmail.com`

***3. Show Git configuration***

`git config --global --list`

***4. Generate special SSH keys and add one of them (public) to your GitHub account***

`ssh-keygen`

***5. Initiate a new local repository***

`git init`

***6. Connect the local repository to GitHub***

`git remote add origin <adress.git>`

***7. Clone a new repository from Github***

`git clone <adress.git>`

***8. Download and update the local repository with content from the remote repository***

`git pull origin main`

***9. Viewing the status of files and folders whose changes have not been added to the repository***

`git status`

***10. Add all changes to the repository (or each file separately)***

`git add .`

***11. Take a snapshot of the current state of changes in the repository and add a description***

`git commit -m "Description of changes"`

***12. Pushing the changes made in the local repository to the remote repository***

`git push`

