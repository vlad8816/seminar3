# Инструкция по работе с Git 

Git - это программа...

## Создание нового репозитория

Чтобы создать новый репозиторий ( инициализировать) нужно ввести команду: 

    git init


git log --oneline - делает все логи в одну строку
git checkout master - возвращает на основную ветку

## Проверка актуального состояния репозитория

Для того, чтобы проверить в каком состоянии находится репозиторий нужно ввести команду:

    git status

git add <имя файла > - Добавление файла в репозиторий для отслеживания

git commit - создание коммита 
git commit -m "message" - создание коммита с комментарием 
git commit -am "message"

git diff
git diff <hash1> <hash2>

git checkout <hash>

git log
git log --oneline

got log --all

git log --all --oneline