# Инструкция по работе с Git

Данная инструкция для помощи в дальнейшей работе с git

## Создание репозитория

Для создания репозитория (инициализация) команда

   git init

## Создание коммитов

  git add ...file name
  
  git commit -m "text"

### Добавление версионности

### Просмотр состояния

  git status

### Создание коммита

  git commit -m "text"

  git diff - сравнение

  git log - логи

  git checkout - метка HEAD

## Создание веток

Для создания ветки команда:

  git branch branch_name

## Переход между ветками

Для перехода между ветками команда:

  git checkout branch_name

## Удаление ветки

Для удаления ветки команда:

  git branch -d branch_name

## Удаленный репозиторий
  
  git remote add origin https://github.com/GDI-hub/git_instruction.git

  git branch -M main

  git push -u origin main