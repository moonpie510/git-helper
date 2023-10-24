# Команды для работы с git

**git init** - инициализируем репозиторий. Мы говорим что теперь наша папка это git репозиторий. В результате будет создана папка (*.git* - служебная папка, история изменений).

**rm -rf .git** - разгитить папку, для этого нужно удалить папку .git.

**git status** - выводит информацию о репозитории.

**git add "test.txt"** - добавлет файлы для коммита, то есть мы говорим какие файлы и какую версию нужно сохранить. Можно добавить все файлы если прописать флаг **--all** или добавить всю папку , используя ".".

**git commit -m "Присвоить коммиту сообщение"** - закомитить, то есть сохранить текущую версию файла/проекта.

**git log** - просмотреть историю коммитов.

**git remote add origin "URL удаленного репозитория"** - привязываем удаленный репозиторий к локальному. *origin* - имя удалённого репозитория, обычно используют origin.

**git remote -v** - команда, которая позволяет убедиться что репозитории связаны.

**git push -u origin master** - отправляем изменения на удаленный репозиторий. В первый раз вызываем с *-u origin master*, а дальше без этого.

