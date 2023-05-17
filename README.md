GIT Homework 1

JSON
 4. Создать внешний репозиторий c названием JSON. Create repository/JSON/add a README.file/Code (copy HTTPS)
 5. Клонировать репозиторий JSON на локальный компьютер. git clone https://github.com/ElKo3006/JSON.git
 6. Внутри локального JSON создать файл “new.json”. cd JSON ; cat > new.json
 7. Добавить файл под гит. git add . (либо git add new.json)
 8. Закоммитить файл. 	git commit -m “create_file”
 9. Отправить файл на внешний GitHub репозиторий. git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. 	
cat > new.json  { "name" : "Kovalskaya Alena", "age" : 27, "pets" : 1, "sallary" : 1000 }
11. Отправить изменения на внешний репозиторий.  git add new.json; git commit -m “mod”; git push
12. Создать файл preferences.json 	cat > preferences.json
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. 	{ "movie" : "The Lord of the Rings"                    
"series" : "Supernatural" 
"food" : "cheese"
"season" : "summer"
"country" : "Spain" }
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON cat > skills.json  "skills" : "test design techniques, working with Terminal, mySQL, Postman, Android studio"
15. Отправить сразу 2 файла на внешний репозиторий. git add .
16. На веб интерфейсе создать файл bug_report.json. Add file/Create new file
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
20. Синхронизировать внешний и локальный репозиторий JSON git pull


XML
 21. Создать внешний репозиторий c названием XML.
 22. Клонировать репозиторий XML на локальный компьютер. git clone https://github.com/ElKo3006/XML.git
 23. Внутри локального XML создать файл “new.xml”. cat > new.xml
 24. Добавить файл под гит.	git add 'new.xml'
 25. Закоммитить файл. 	git commit -m “new_xml_file”
 26. Отправить файл на внешний GitHub репозиторий. git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. 
cat > new.xml 
<?xml version="1.0" encoding="UTF-8"?>                 
<info>
<name>Kovalskaya Alena</name>
<age>27</age>
<pets>1</pets>
<salary>1000</salary>
</info>
 28. Отправить изменения на внешний репозиторий. git add ‘new.xml’; git commit -m “update_xml”; git push
 29. Создать файл preferences.xml cat > preferences.xml 
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. 
<?xml version="1.0" encoding="UTF-8"?>
<info>
<movie>The Lord of the Ring</movie>
<series>Supernatural</series>
<food>cheese</food>
<season>summer</season>
<country>Spain</country>
</info>
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
<?xml version="1.0" encoding="UTF-8"?>
<skills>test design techniques, working with Terminal, mySQL, Postman, Android studio</skills>
 32. Сделать коммит в одну строку. 	git add .; git commit -m “cretae_skils_xml”;
 33. Отправить сразу 2 файла на внешний репозиторий. 	git push
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML	 git pull

TXT
 1. Создать внешний репозиторий c названием TXT. Create repository/TXT/Code (copy HTTPS)
 2. Клонировать репозиторий TXT на локальный компьютер.  git clone https://github.com/ElKo3006/TXT.git
 3. Внутри локального TXT создать файл “new.txt”. cat > new.txt
 4. Добавить файл под гит. git add ‘new.txt’
 5. Закоммитить файл.	git commit -m “create_txt”
 6. Отправить файл на внешний GitHub репозиторий. git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT cat > new.txt
ФИО Ковальская Елена Сергеевна
возраст 27 лет
количество домашних животных 1
будущая желаемая зарплата 1000
^C
 8. Отправить изменения на внешний репозиторий.	git add new.txt; git commit -m "update_txt"; git push
 9. Создать файл preferences.txt.  cat > preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT. 
любимый фильм Властелин колец
любимый сериал Сверхъестественное
Любимая еда Сыр
Любимое время года Лето
страна Испания
^C
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT cat > skills.txt 
 git add .;git commit -m "create_skills";
 cat > skills.txt 
Информация о скиллах: техники тест-дизайна, работа с БД, Terminal, Postman, Android Studio
^C
 12. Сделать коммит в одну строку.	 git commit -a -m "update_pr_sk";
 13. Отправить сразу 2 файла на внешний репозиторий. 	git push
 14. На веб интерфейсе создать файл bug_report.txt.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT git pull
