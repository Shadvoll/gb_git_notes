# Инструкция для работы с Git и удалёнными репозиториями
## __Что такое Git?__
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## __Подготовка репозитория__
Для создание репозитория необходимо выполнить команду  *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## __Добавлений изменений__

* ### **Добавление изменений.** 
    Git add Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add* <имя файла>

* ### __Просмотр состояния репозитория.__ 
    Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

* ### __Создание коммитов.__ 
    Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>"*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

* ### __Добавление изменений и создание коммита.__  
    Для того, чтобы сразу добавить изменения и создать коммит. Можно прописать *git commit -am "<Сообщение к коммиту>"*

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

## Полезные команды:
    
### Обновить ветку *master* с сервера

    git pull origin master 

*(pull - c англ. тянуть)*

### Загрузить/Обновить данные на сервере

    git push origin master

или другую ветку:

    git checkout <название_ветки>
    git push origin <название_ветки>

*(push - толкать)*
### Подгрузить/соеденить свой local git с github

    git remote add origin https://github.com/ <Shadvoll/Название репо.git>

### GitHub *pull request*
1. Делаем fork интересующего репозитория.
2. Мы делаем git clone для нашей версии  этого репозитория
3. Мы создаем ветку с предлагаемыми изменениями
4. Производим все изменения **только в этой ветке**
5. Оправляем эти изменения *push*
6. В окне GitHub появляет кнопка *pull request*

# Полезные советы от Ильнара Шафигуллина 

1. Про папки и репозитории
    + отслеживать изменения файлов
    + хранить информацию о ветках

    **Важно! Репозиторий не возникает сам по себе, его нужно создать.** *(Или клонировать)*

2. Как понять, в репозитории мы находимся или в папке
    
    Команда

        git status
    Помогает понять находимся ли мы репозитории или нет. В случае если выскочит ошибка, значит данная папка не репозиторий.
3. Как можно создать репозиторий

        git init
        git clone
    **git init** - позволяет создать репозиторий 

    **git clone** - клонируем репозиторий из удаленного хранилища, из GitHub
4.  Внимательно следим за тем, из какой папки вы вызываете команды

5. Не нужно создавать репозитории внутри другого репозитория

6. Как репозиторий сделать обычной папкой
    
    Удалить папку *.git* внутри папки-репозитория

## [Ссылка на GB](https://gb.ru/posts/soveti-pro-git)



# Полезные ссылки
1. [Git для новичков (часть 1)](https://habr.com/ru/post/541258/)
2. [Git для новичков (часть 2)](https://habr.com/ru/post/542616/)
3. [Тренажер git](https://learngitbranching.js.org/?locale=ru_RU) ![Тренажер git имеет подсказки](/scrshot_git_trainer.png)



