# Домашнее задание к занятию «Основы Git»

## Задание 1. Знакомимся с GitLab и Bitbucket

Создала аккаунт в Gitlab и новый публичный проект devops-netology.

![Создала аккаунт в Gitlab](start_gitlab.png)

Вывод команды `git remote -v` до подключения к удаленному репозиторию.

![remote_1](remote_1.png)

Подключаем удаденный репозиторий и выполняем push.

![push_gitlab](push_gitlab.png)

Вывод команды `git remote -v` после подключения к удаленному репозиторию.

![remote_2](remote_2.png)

## Задание 2. Теги

Создаем легковесный тег `v0.0` и пушим его в репозитории.

![tag_1](tag_1.png)

![push_tag_1](push_tag_1.png)

Создаем аннотированный тег `v0.1` и пушим его в репозитории.

![tag_2](tag_2.png)

![push_tag_2](push_tag_2.png)

Вывод команды git show будет отличаться для тегов. Для легковесного тега мы сразу увидим хеш коммита, а для аннотированного в начале будет дата и кто тегировал.

Теги в Github

![tags_github](tags_github.png)

Теги в Gitlab

![tags_gitlab](tags_gitlab.png)

## Задание 3. Ветки

Схема сразу после добавления ветки fix.

![graph_1](graph_1.png)

Схема после изменения файла в ветке fix.

![graph_2](graph_2.png)

Вывод команды `git log`.

![log_new_branch](log_new_branch.png)

## Задание 4. Упрощаем себе жизнь

![editor](editor.png)

