# **инструкция по работе Git**]

## Предварительная рстройка Git

Чтобы "представиться" программе git нужно ввести команды :

    git config --global user.name "Ваше имя"
    git config --global user.email "Вашь e-mail"

## создание репозитория

Чтобы инициализировать новый репозиторий нужно ввести команду :

    git init

## Добавление в индекс

Чтобы добавить изменения в индекс (для фиксации в следующем комите) нужно ввести команду :

    git add <имя файла>

 ## Фиксация инменений

 Чтобы зафиксировать изменения , добавленные в индекс нужно ввести команду :

    git commit  


    git status

    git commit -m "сообщение"
    git commit -a
    git commit -am "сообщение"

    git log
    git log --oneline
    git log --all
    git log --all --oneline

    git diff
    git diff "hash1" "hash2"

    git checkout "hash"
    git checkout master