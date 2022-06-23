## В данном репозитории представлена домашняя работа по работе с ветками в Git
### Git_hw
 
1.На локальном репозитории сделать ветки для: 

+ Postman - `git branch Postman` 

+ Jmeter - `git branch Jmeter`
+ CheckLists - `git branch CheckLists`
+ Bug Reports - `git branch Bug_Reports`
+ SQL - `git branch SQL`
+ Charles - `git branch Charles`
+ Mobile testing - `git branch Mobile_testing` 


2.Запушить все ветки на внешний репозиторий - `git push -u origin --all` 


3.В ветке Bug Reports сделать текстовый документ 
со структурой баг репорта - `git checkout Bug_Reports` ; `cat > str.bug_rep.txt;`



4.Запушить структуру багрепорта на внешний репозиторий -` git add . ; git commit -m "add str.bug_rep.txt" ; git push;` 


5.Вмержить ветку Bug Reports в Main - `git checkout main ; git merge Bug_Reports;`

6.Запушить main на внешний репозиторий - `git add . ; git commit -m "merge Bug report to master;" ; git push;` 


7.В ветке CheckLists набросать структуру чек листа - `git checkout CheckLists ; cat > str.cheklist.txt;` 




8.Запушить структуру на внешний репозиторий - `git add . ; git commit -m "add str.checklist.txt" ; git push;`

9.На внешнем репозитории сделать Pull Request ветки CheckLists в main - Перейти на веб версию github в нужный репозиторий, изменить ветку на Checklists, нажать Pull Request

10.Синхронизировать Внешнюю и Локальную ветки Main - `git checkout main ; git pull;`
