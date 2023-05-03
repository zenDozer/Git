# Git commands

### HW #1

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


### HW #2

***1. На локальном репозитории сделать ветки для:***
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bag_Reports
git branch SQL
git branch Charles
git branch Mobile_testing
```

***2. Запушить все ветки на внешний репозиторий***

```
git push --all
```

***3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта***

```
git checkout Bag_Reports
vim br.txt
```

***4. Запушить структуру багрепорта на внешний репозиторий***

```
git add .
git commit -m "Add br.txt"
git push -u origin Bag_Reports
```

***5. Вмержить ветку Bag Reports в Main***

```
git checkout main
git merge CheckLists
```

***6. Запушить main на внешний репозиторий.***

```
git push
```

***7. В ветке CheckLists набросать структуру чек листа.***

```
git checkout CheckLists
vim cl.txt
```

***8. Запушить структуру на внешний репозиторий***

```
git add .
git commit -m "Add checklist file cl.txt"
git push -u origin CheckLists
```

***9. На внешнем репозитории сделать Pull Request ветки CheckLists в main***

```
GitHub -> Git repositori -> CheckLists had recent pushes less than a minute ago -> 
Compare & Pull requests -> Create pull request -> Merge pull request -> Confirm merge
Pull request successfully merged and closed
```

***10. Синхронизировать Внешнюю и Локальную ветки Main***

```
git checkout main
git pull
```