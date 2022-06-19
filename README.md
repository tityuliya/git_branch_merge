___GitHub. HW_2___


1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists 
- Bug Reports
- SQL
- Charles
- Mobile testing

```
git clone https://github.com/tityuliya/git_branch_merge.git

git branch Postman
git branch Jmeter
git branch CheckLists
git branch BugReports
git branch SQL
git branch Charles
git branch MobileTesting
```

2. Запушить все ветки на внешний репозиторий
```
git push -u origin Postman
git push -u origin Jmeter
git push -u origin CheckLists
git push -u origin BugReports
git push -u origin SQL
git push -u origin Charles
git push -u origin MobileTesting
```

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
```
git checkout BugReports
vim BugReport.txt
```

4. Запушить структуру багрепорта на внешний репозиторий
```
git add .
git commit -m "add BugReport"
git push
```

5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge BugReports
```

6. Запушить main на внешний репозиторий
```
git push
```

7. В ветке CheckLists набросать структуру чек листа
```
git checkout CheckLists
vim CheckList.txt
```

8. Запушить структуру на внешний репозиторий
```
git add .
git commit -m "add CheckList"
git push
```

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```

```

10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git fetch
git pull
```
