### GIT Homework 1   
## Сценарий   
 |Шаги|JSON|XML|TXT|
 |:--|:--|:--|:--|
 |4. Создать внешний репозиторий c названием... |github.com/new -> <br/> Repository name JSON (Add readme.md) -> <br/> Create repository|||
 |5. Клонировать репозиторий на локальный компьютер|git clone https://github.com/OlgaVyunik/JSON.git |||
 |6. Внутри локальной директории создать файл | cd JSON <br/>  touch new.json |||
 |7. Добавить файл под гит | git add new.json |||
 |8. Закоммитить файл |git commit -m "new"|||
 |9. Отправить файл на внешний GitHub репозиторий |git push|git push|git push|
 |10. Отредактировать содержание файла - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в соответствующем формате| start new.json - edit - save|||
 |11. Отправить изменения на внешний репозиторий |git add new.json  <br/>  git commit -m "update" <br/>  git push |||
 |12. Создать файл | touch preferences.json |||
 |13. В файл добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) | start preferences.json - edit - save |||
 |14. Создать файл добавить информацию о скиллах которые будут изучены на курсе в формате JSON | touch skills.json  <br/>   start skills.json - edit - save |||
 |15. Отправить сразу 2 файла на внешний репозиторий. | git add . <br/>   git commit -am "new"  git push|git add .  <br/>  git commit -am "new" <br/> git push|git add .    git commit -am "new"  git push|
 |16. На веб интерфейсе создать файл | Add file - bug_report.json.|||
 |17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.|Commit new file|||
 |18. На веб интерфейсе модифицировать файл, добавить баг репорт в соответствующем формате |Edit this file|||
 |19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.|Commit changes|||
 |20. Синхронизировать внешний и локальный репозиторий |git pull|||
