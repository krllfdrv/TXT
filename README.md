1. Создать внешний репозиторий c названием TXT. 
 2. Клонировать репозиторий TXT на локальный компьютер.  
`mkdir TXT`  
`cd TXT`  
`git clone https://github.com/krllfdrv/TXT.git`  
 3. Внутри локального TXT создать файл “new.txt”.  
`cd TXT`  
`touch new.txt`  
`git status`  
 4. Добавить файл под гит.   
`git add new.txt`  
`git status`  
 5. Закоммитить файл.  
`git commit -m "Txt"`  
 6. Отправить файл на внешний GitHub репозиторий.   
`git push`  
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
`vim new.txt`  
`cat new.txt`  
 8. Отправить изменения на внешний репозиторий.   
`git status`  
`git commit -am "added main info"`  
`git push`  
 9. Создать файл preferences.txt   
`touch preferences.txt`  
 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.   
`vim preferences.txt`  
`cat preferences.txt`  
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT   
`touch sklls.txt`  
`vim sklls.txt`  
`cat sklls.txt`  
 12. Сделать коммит в одну строку. 
 13. Отправить сразу 2 файла на внешний репозиторий.  
`git status`  
`git add  preferences.txt sklls.txt`  
`git status`  
`git commit -m "added sklls and preferences"`  
`git push`  
 14. На веб интерфейсе создать файл bug_report.txt.   
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT. 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 18. Синхронизировать внешний и локальный репозиторий TXT   
`git pull`
