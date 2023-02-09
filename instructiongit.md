## GIT - программа для контроля версий!
### __Команды GIT:__
~~Начало работы~~
* git version - проверка версии 
* git init - инициализация репозитория
* git add - добавить файл в очередь коммита
* git commit - m "initial commit" - создание первого коммита
* git commit -m "text" - сделать еще один коммит с текстом text
* git commit -a -m "text" - сохраняет два коммита
* git status - проверка текущего состояния 
* git log - журнал изменений 
* git checkout - переключение между версиями 
* git checkout master(main) - возврат к текущей версии 
* git diff - покавает разницу между текущими файлами и сохраненными
* git config --global user.email "@" user.name "name" - добавление имени и почты
* touch + наз.папки - создание папки
* NUL > наз.папки - создание папки
* pwd - проверка имени пути папки 
* q - возврат в исходное окно терминала 
* git commit --amend -m - изменяет текст последнего коммита 
* touch <название папки> - создать новую папку

__Создание веток:__

1) git branch <название ветки> - создать новую ветку
2) git branch --all - посмотреть все ветки 
3) git branch -d <название ветки> - удаление ветки 
4) git branch -m <название ветки> - переименование и переход на новую ветку

__Работа с ветками:__

1) git log --oneline --all --graph - видно все изменения коммита
2) git ignore - исключает ненужные файлы из загрузки
3) cd <название репозитория> - переход на новый репозиторий 
4) git merge <название ветки> - слияние веток изменение коммита 

__Работа с удаленными репозиториями:__

1) git clone <ссылка на репозиторий> - копирование удаленного репозитория 
2) cd <название папки> - поменять дерикторий 
3) git push - направить нашу версию на удаленный репозиторий 
4) git pull - скачать из текущего репозитория и сделать merge c нашей версией 
5) git remote add origin <ссылка> - связывает локальный и удаленный репозиторий 
6) pull request - команда для предложения изменений 
7) fork - ответвление от репозитория 