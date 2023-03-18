---
title: Система контроля версий Git
subtitle:  VCS

# Summary for listings and search engines
summary: 

# Link this post with a project
projects: []

# Date published
date: '2023-03-18T00:00:00Z'

# Date updated
lastmod: '2023-03-18T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit [About Github](https://www.thurrott.com/cloud/278695/github-crosses-100-million-developers-milestone)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Контроль версий
  - Гитхаб
  - Github

categories:
  - Demo
---

```python
import libr
print('hello, world!')
```
## What is that?

- Система контроля версий Git представляет собой набор программ командной строки. 
Доступ к ним можно получить из терминала посредством ввода команды git с различными опциями.

- Благодаря тому, что Git является распределённой системой контроля версий, резервную копию локального хранилища можно сделать простым копированием или архивацией.

## Основные команды git:

Например, в табл. @tbl:std-dir приведено краткое описание основных команд Git.

: Описание некоторых команд системы контроля версий Git {#tbl:std-dir}

| Команда | Описание команды                                                                 |
|--------------|-------------------------------------------------------------------------------------------|
| `git init`     | Создание основного дерева репозитория  |
| `git pull`     | Получение обновлений(изменений текущего дерева из центрального репозитория |
| `git push`     | Отправка всех произведённых изменений локального дерева в центральный репозиторий |
| `git status`   | Просмотр списка изменённых файлов в текущей директории |
| `git diff`     | Просмотр текущих изменений  |
| `git add .`    | Добавление все изменённые и/или созданные файлы и/или каталоги |
| `git rm имена_файлов` | Удаление файлов и/или каталогов из индекса репозитория |
| `git commit -am 'Описание коммита'`| Сохранение всех добавленных изменений и всех изменённых файлов |
| `git commit`   | Сохранение добавленный изменений с внесением комментария через встроенный редактор |
| `git checkout -b имя_ветки` | Создание новой ветки, базирующейся на текущей | 
| `git branch -d имя_ветки` | Удаление локальной уже слитой с основным деревом ветки |
| `git branch -D имя_ветки` | Принудительное удаление локальной ветки |

Полный список команд можно посмотреть на официальном сайте: [Github.com](https://docs.github.com/en/get-started/using-github/github-command-palette)
