### GIT Homework 1   
#### Сценарий   
 |Шаги|JSON|XML|TXT|
 |:--|:--|:--|:--|
 |4. Создать внешний репозиторий c названием... |github.com/new  <br/> -> Repository name JSON (Add readme.md)<br/> ->  Create repository|github.com/new  <br/> -> Repository name XML (Add readme.md)<br/> ->  Create repository|github.com/new  <br/> -> Repository name TXT (Add readme.md)<br/> ->  Create repository|
 |5. Клонировать репозиторий на локальный компьютер|git clone [link](https://github.com/OlgaVyunik/JSON.git) |git clone [link](https://github.com/OlgaVyunik/XML.git)|git clone [link](https://github.com/OlgaVyunik/TXT.git)|
 |6. Внутри локальной директории создать файл | cd JSON <br/>  touch new.json |cd XML <br/>  touch new.xml|cd TXT <br/>  touch new.txt|
 |7. Добавить файл под гит | git add new.json |git add new.xml|git add new.txt|
 |8. Закоммитить файл |git commit -m "new"|git commit -m "new"|git commit -m "new"|
 |9. Отправить файл на внешний GitHub репозиторий |git push|git push|git push|
 |10. Отредактировать содержание файла - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в соответствующем формате| start new.json -> edit -> save|start new.xml -> edit -> save|start new.txt -> edit -> save|
 |11. Отправить изменения на внешний репозиторий |git add new.json  <br/>  git commit -m "update" <br/>  git push |git add new.xml  <br/>  git commit -m "update" <br/>  git push|git add new.txt  <br/>  git commit -m "update" <br/>  git push|
 |12. Создать файл | touch preferences.json |touch preferences.xml|touch preferences.txt|
 |13. В файл добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) | start preferences.json -> edit -> save |start preferences.xml -> edit -> save |start preferences.txt -> edit -> save |
 |14. Создать файл добавить информацию о скиллах которые будут изучены на курсе | touch skills.json  <br/>   start skills.json -> edit -> save |touch skills.xml  <br/>   start skills.xml -> edit -> save |touch skills.txt  <br/>   start skills.txt -> edit -> save |
 |15. Отправить сразу 2 файла на внешний репозиторий. | git add . <br/>   git commit -am "new" <br/> git push|git add .  <br/>  git commit -am "new" <br/> git push|git add .  <br/>  git commit -am "new" <br/> git push|
 |16. На веб интерфейсе создать файл | "Add file" -> bug_report.json|"Add file" -> bug_report.xml|"Add file" -> bug_report.txt|
 |17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.|"Commit new file"|"Commit new file"|"Commit new file"|
 |18. На веб интерфейсе модифицировать файл, добавить баг репорт в соответствующем формате |"Edit this file"|"Edit this file"|"Edit this file"|
 |19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.|"Commit changes"|"Commit changes"|"Commit changes"|
 |20. Синхронизировать внешний и локальный репозиторий |git pull|git pull|git pull|
