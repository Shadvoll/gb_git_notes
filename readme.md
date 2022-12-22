# Инструкция для работы с Git и удалёнными репозиториями
## __Что такое Git?__
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## __Подготовка репозитория__
Для создание репозитория необходимо выполнить команду  *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## __Добавлений изменений__

* ### __Добавление изменений.__ Git add Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add* <имя файла>

* ### __Просмотр состояния репозитория.__ Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

* ### __Создание коммитов.__ Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>"*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

* ### __Добавление изменений и создание коммита.__  Для того, чтобы сразу добавить изменения и создать коммит. Можно прописать *git commit -am "<Сообщение к коммиту>"*

## Перемещение между сохранениями

## Журнал изменений
1. __git log__
2. __git checkout__

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*



## Ветки в Git
* ### __Создание ветки.__ Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

* ### __Слияние веток.__ Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*

* ### __Удаление веток.__ Для удаления ветки ввести команду *git branch -d 'name branch'*

## Удаленные репозитории
1. ### Git 
    **Git** — это программа, которая устанавливается на компьютер, где локально выполняет
указанные вами команды
2. ### GitHub
    **GitHub** это сервис компании Microsoft, который позволяет интегрироваться с
программой Git и настроить удалённую работу с вашим репозиторием

Таким образом, вы можете работать локально или хранить свой репозиторий на GitHub,
используя команды, входящие в программу Git


# Полезные ссылки
1. [Git для новичков (часть 1)](https://habr.com/ru/post/541258/)
2. [Git для новичков (часть 2)](https://habr.com/ru/post/542616/)
3. [Тренажер git](https://learngitbranching.js.org/?locale=ru_RU) ![Тренажер git имеет подсказки](/scrshot_git_trainer.png)



