Создать внешний репозиторий c названием XML === На вэбе Repositories --> New --> Repos Name:XML --> Check "Add a README file" --> Press "Create repository"
Клонировать репозиторий XML на локальный компьютер === git clone <repository_linkHTTPS>
Внутри локального XML создать файл “new.xml” === touch new.xml
Добавить файл под гит === git add new.xml
Закоммитить файл === git commit -m "comment"
Отправить файл на внешний GitHub репозиторий === git push
Отредактировать содержание файла “new.xml” написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата) === vim new.xml
Отправить изменения на внешний репозиторий === git commit -am "comment" --> git push
Создать файл preferences.xml === touch preferences.xml
В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) === vim preferences.xml
Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML === vim skills.xml
Сделать коммит в одну строку === git add . && git commit -m "comment"
Отправить сразу 2 файла на внешний репозиторий === git push
На веб интерфейсе создать файл bug_report.xml === Add file --> Create new file --> Name: bug_report.xml
Сделать Commit changes (сохранить) изменения на веб интерфейсе === Commit New File
На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML === Choose bug_report.xml --> Edit this file
Сделать Commit changes (сохранить) изменения на веб интерфейсе === Commit changes
Синхронизировать внешний и локальный репозиторий XML === git pull
