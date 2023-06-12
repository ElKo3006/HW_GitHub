GIT Homework 2

1. На локальном репозитории сделать ветки для:  
- Postman - Jmeter - CheckLists - Bag Reports - SQL - Charles - Mobile testing  
```
git branch Postman 
git branch Jmeter 
git branch CheckLists 
git branch Bug_Reports
git branch SQL
git branch Charles
git branch Mobile_testing
``` 
2. Запушить все ветки на внешний репозиторий  ```git push --all```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта ```git checkout Bag_Reports;``` ```cat > structureBR.txt; git add structureBR.txt; git commit -m "createSBR";``` 
4. Запушить структуру багрепорта на внешний репозиторий  ```git push -u origin Bug_Reports```
5. Вмержить ветку Bag Reports в Main  ```git checkout main; git merge Bug_Reports```
6. Запушить main на внешний репозиторий.  ```git push -u origin main```
7. В ветке CheckLists набросать структуру чек листа. ```git checkout CheckLists;``` ```cat > structure_ChL.txt; git add structure_ChL.txt; git commit -m "createSCHL";```
8. Запушить структуру на внешний репозиторий  ```git push -u origin CheckLists```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  ```Pull Request/Create pull request```
10. Синхронизировать Внешнюю и Локальную ветки Main ```git checkout main; git pull```
