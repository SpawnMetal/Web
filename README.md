# Web Notes

- [Use](#Use)
- [Git](#Git)
- [JavaScript](#JavaScript)
  - [ECMAScript](#ECMAScript)
  - [IIFE](#IIFE)
  - [Классы](#Классы)
  - [Контекст](#Контекст)
  - [Декларативное, Императивное программирование](#Декларативное-Императивное-программирование)
  - [Declaration, Expression Function](#Declaration-Expression-Function)
  - [Анонимная функция](#Анонимная-функция)
  - [JSON](#JSON)
  - [use strict](#use-strict)
  - [Генераторы](#Генераторы)
  - [Шаблонные литералы](#Шаблонные-литералы)
  - [Promise](#Promise)
  - [Код](#Код)
  - [W3C DOM Events](#W3C-DOM-Events)
  - [Деструктуризация](#Деструктуризация)
  - [Тернарный оператор](#Тернарный-оператор)
  - [Динамический ключ](#Динамический-ключ)
  - [Прототипы](#Прототипы)
  - [Операторы](#Операторы)
  - [Чистая функция](#Чистая-функция)
  - [freeze](#freeze)
  - [Дескрипторы](#Дескрипторы)
  - [Reflect](#Reflect)
  - [Proxy](#Proxy)
  - [??](#??)
  - [?.](#?.)
  - [Типы данных](#Типы-данных)
  - [new](#new)
  - [delete](#delete)
  - [reduce](#reduce)
  - [for](#for)
  - [Регулярные выражения](#Регулярные-выражения)
- [Technology](#Technology)
  - [React](#React)
    - [JSX](#JSX)
  - [NestJS](#NestJS)
  - [GraphQL](#GraphQL)
  - [Docker](#Docker)
  - [TypeORM](#TypeORM)
  - [Babel](#Babel)
  - [Material Design](#Material-Design)
  - [Axios](#Axios)
  - [Lodash](#Lodash)
  - [Webpack](#Webpack)
  - [JScript](#JScript)
  - [CoffeeScript](#CoffeeScript)
  - [Flow](#Flow)
  - [Dart](#Dart)
  - [Angular](#Angular)
  - [AngularJS](#AngularJS)
  - [RxJS](#RxJS)
  - [Open Server](#Open-Server)
  - [Xampp](#Xampp)
  - [Electron JS](#Electron-JS)
  - [Cleave.js](#Cleave.js)
  - [Emmet](#Emmet)
  - [JSON Web Token (JWT)](#JSON-Web-Token-JWT)
  - [Nx](#Nx)
  - [Meteor](#Meteor)
  - [WebSocket](#WebSocket)
  - [Контейнеризация](#Контейнеризация)
  - [Markdown](#Markdown)
- [Stacks](#Stacks)
  - [MERN](#MERN)
- [Flux-архитектура](#Flux-архитектура)
- [Автотесты](#Автотесты)
- [Принципы](#Принципы)
  - [Принципы, схемы и подходы программирования](#Принципы, схемы и подходы программирования)
  - [Реактивное программирование](#Реактивное программирование)
  - [SaaS](#SaaS)
- [IDE](#IDE)
  - [VSCode](#VSCode)
  - [WebStorm](#WebStorm)
- [Генератор документации](#Генератор-документации)
- [Облачные сервисы](#Облачные-сервисы)
- [API](#API)
  - [REST, Open API](#REST-Open-API)
- [Транспиляция](#Транспиляция)
  - [Bundle](#Bundle)
- [Cookie](#Cookie)
- [Определения](#Определения)
  - [Нативный](#Нативный)
  - [Адаптивность, Отзывчивость](#Адаптивность-Отзывчивость)
  - [Accessibility](#Accessibility)
  - [#Семантика](#Семантика)
  - [Layout](#Layout)
  - [Legacy code](#Legacy-code)
  - [Миксин](#Миксин)
  - [Палиндром](#Палиндром)
  - [Сборка мусора](#Сборка-мусора)
  - [Веб-безопасность](#Веб-безопасность)
  - [Полифил](#Полифил)
  - [Микросервис](#Микросервис)
- [HTML](#HTML)
- [CSS](#CSS)
  - [БЭМ](#БЭМ)
- [Шрифты](#Шрифты)
- [Typescript](#Typescript)
  - [enum](#enum)
- [Браузер](#Браузер)
- [Алгоритмы и структуры данных](#Алгоритмы-и-структуры-данных)
- [NoSQL](#NoSQL)
  - [Redis](#Redis)
- [Брокер](#Брокер)
- [Процесс разработки программного обеспечения, Жизненный цикл, MVP](#Процесс-разработки-программного-обеспечения-Жизненный-цикл-MVP)

## Use

#Соглашения JavaScript
#React
#MobX
#NestJS
#Typeorm
#GraphQL
#Swagger
#Typescript
#Jest
[Git]
#MVC
#Material Design
#WebSocket
#Docker
#SASS
#VSCode #VSCodeРасширения
#JSDoc и readme.md
#БЭМ

## Git

`#Git`

Git (произносится «гит») — распределённая система управления версиями.
https://ru.wikipedia.org/wiki/Git
Офф: https://git-scm.com/docs
Atlassian: https://www.atlassian.com/ru/git/tutorials/setting-up-a-repository
https://youtu.be/zZBiln_2FhM
https://habr.com/ru/post/106912
Путь от и до: https://rustycrate.ru/руководства/2016/03/07/contributing.html
Плагин для Chrome - Octotree - GitHub code tree: https://chrome.google.com/webstore/detail/octotree-github-code-tree/bkhaagjahfmjljalopjnoealnfndnagc?hl=ru

### Обозначения

Repository - репозиторий, в нём находится весь проект, как правило ему задаём имя upstream
Branch - ветка
Fork - ответвление, копия репозитория (в переводе вилка). Запрос на слияние форков и будет pull request
HEAD - последний коммит в ветке, можно юзать везде, где указывается id
origin - имя текущего репозитория. Указывается в команде git remote add для работы со своим репозиторием / форкой. Создаётся при git clone
upstream - имя основной серверной репы. Указывается в команде git remote add для работы с репой источником, исходником, оригиналом
master - основная ветка в репе, которая создаётся автоматом вместе с репой
. - все, например, файлы
& - для перечисления нескольких команд git и cmd. В powershell для перечисления нескольких команд используется точка с запятой

### Персональные данные

git config --global user.name <"name"> - если name не указан, выведет текущий UserName, иначе задаст его
git config --global user.email <"email"> - если email не указан, выведет текущий UserEmail, иначе задаст его
git config --global http.sslverify false - отключить использование сертификата

### Общие

git --version - версия
git --help - список команд
gitk --all& - графический интерфейс гита
.gitignore - файл для объектов исключений, которые не будем добавлять в отслеживание, проект

### Проект

#clone: git clone <remote_url> - скопировать содержимое проекта. В текущую папку git clone <remote_url> . - с точкой вконце, скопирует содержимое в корень текущей директории, не создавая папку. Команда создаёт скрытую системную папку ".git" и делает git add origin
git init - инициализация проекта. Команда создаёт скрытую системную папку ".git"
git remote add <remote_name> <remote_url> - привязать проект remote_url к названию remote_name. Не ветке, просто названию, чтобы не писать длинную ссылку постоянно. Например remote_name = origin
git remote show <remote_name> - показать информацию об удалённом репозитории, ветке, HEAD и т д
git remote -v - покажет все добавленные remote_url и их remote_name
git remote rm <remote_name> - удалить привязку remote_name к remote_url из списка

### Комбо

#Персональные данные: git config --global user.name "name" & git config --global user.email "email" & git config --global http.sslverify false
Init & GitHub: git init & git add . & git commit -m "First commit" & git branch -M main & git remote add origin https://github.com/SpawnMetal/lib.git & git push -u origin main
#Файлы Update: git add . & git commit -m "Updated date" & git push
#Файлы Синхронизация: git add . & git commit -m "" & git pull origin <branch> & git push
#Ветки Удаление ветки: git checkout develop & git branch -d <branch> & git push <remote_name> <branch> --delete

### Файлы

git push -u <remote_name> <branch> - Заливает новую branch в remote_name. Создаёт pull request, если ветка уже есть. -u -это upstream, мол сервер. Например выполнив команду git push -u origin master вы устанавливаете связь между той веткой, в которой вы находитесь и веткой master на удалённом сервере. Команду требуется выполнить единожды, чтобы потом можно было отправлять/принимать изменения лишь выполняя git push из ветки без указания всяких алиасов для сервера и удалённых веток. Это сделано для удобства.
git push - залить в текущую ветку на сервер, ранее должна быть установлена связь git push -u
git push <remote_name> <branch> - заливает изменения по <remote_name> в <branch>
Флаг --force отменяет необходимость в pull и подгоняет ветку удаленного репозитория под вашу локальную ветку, удаляя любые вышестоящие изменения, которые могли быть внесены с момента последнего выполнения вами команды pull.

git pull <remote_name> <branch> - шоткод для команд git fetch и git merge. <remote_name> и <branch> по умолчанию текущие. Получит с сервера и объединит с локальной.
При работе с fork не забывать пуллить свою форку с remote.
--rebase либо git rebase - Перебазирует ветку на текущий и дальнейшие коммиты, которые будут попадать в историю коммитов (например master) на момент её слияния с перебазированной веткой (develop), а не на момент создания коммита в прошлом.
Т.е. коммит сделанный 3 года назад в develop, при слиянии попадёт в самый верх коммитов master. См. Commits on Jun 22, 2022 https://github.com/SpawnMetal/examples/commits/master
Использовать при пулле из upstream в origin https://www.atlassian.com/ru/git/tutorials/syncing/git-pull
git rebase --skip позволит пропустить конфликт при git rebase, для каждого конфликта команда вводится отдельно

git add <file> или . - добавляет file или все файлы в отслеживаемые для добавления в коммит. Несколько перечисляются через пробел.
git fetch <remote_name> <branch> - получить изменения, но не делать слияние - git merge.
git merge <branch> - объединить скачанные изменения с текущей веткой, либо branch, если указана, в таком случае из branch будут получены все изменения
git commit -m <text> - зафиксировать отслеживаемые файлы, создав коммит. -m = -message. text указывается в двойных кавычках. После ввода команды будет выведен хэш коммита
git show <id> просмотр информации о теге, коммите, ветке

git status - показать текущую ветку и изменённые файлы
git clone см #clone
git checkout <id>, <file> либо <tag> - переключиться на id коммита, tag либо откатить файл до индекса. Работает с тремя различными объектами: файлами, коммитами и ветками. Команда открепляет HEAD, что не позволит сохранить изменения при неизбежном переключении обратно в ветку.

Удалить индексы, не файлы, код не бэкапнется. Несколько файлов перечисляются через пробел:
git reset <file>
git rm --cached <file>
git rm -r .

git reset --hard id либо origin/master - откатит код до коммита id либо ветки origin/master, стерев историю
git restore <file> - откатит до коммита (бэкапнет код) не проиндексированные файлы, проиндексированные сначала отменить: git reset <file>
git restore --source <id_коммита> <file> - откатит код до коммита id сохранив историю, создав новый коммит

git show <commit_id> - покажет информацию о коммите и его полный id
git commit --amend -m "" - переименовать либо отредактировать текст последнего коммита
git log -кол-во --pretty=oneline - покажет информацию по кол-ву последних коммитов, теги, сообщения коммитов, HEAD. Напротив последней залитой будет красным написано origin/branch

get tag -a - аннотированный тег, некое название коммита https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository/git-tag https://git-scm.com/book/ru/v2/Основы-Git-Работа-с-метками
git tag -a v1.0.1 -m "" - создать тег
git tag -a -f <tag> -m "" <id> - переименовать тег у коммита id
git tag -a <tag> <id> - задать тег любому коммиту id
git tag - просмотр списка тегов
git show <tag> просмотр информации о теге, коммите, ветке
git tag -d <tag> - удалить тег

### Ветки

git branch - выводит список веток и ветку в которой я нахожусь. В VSCode слева снизу
git branch <branch> - создаст ветку name, копию текущей
git branch -d <branch> - удалит ветку name локально. Необходимо сначала переключиться на другую. -D, если необходимо удалить принудительно (--force)
git pull origin develop - скачать новую ветку с сервера
git push <remote_name> <branch> --delete - удаляет ветку на сервере
git branch -m <branch> - переименовать текущую ветку в name, -M, если необходимо переименовать, даже если такая ветка уже сушествует
git checkout <branch> - переключиться на ветку name
git checkout -b <branch> - создать и переключиться на ветку name, копию текущей
git checkout -b <branch> <remote_name> - создать и переключиться на ветку branch, ответвление от name_from
git checkout -b <branch> <repository_name_from>/<branch> - скопировать удалённую ветку и переключиться в неё
git push -u <remote_name> <branch> - Заливает НОВУЮ!!! branch в remote_name. Создаёт pull request при необходимости. -u: upstream. remote_name: название ссылки, которое устанавливал с помощью git remote add <remote_name> <remote_url>. branch: ветка, которую будем заливать.
git show <branch> просмотр информации о теге, коммите, ветке

#### Release branches

Ветви релизов (release branches) используются для подготовки к выпуску новых версий продукта.
Могут порождаться от: develop
Должны вливаться в: develop и master
Соглашение о наименовании: release-\*

#### Hotfix branches

Они порождаются необходимостью немедленно исправить нежелательное поведение производственной версии продукта.
Могут порождаться от: master
Должны вливаться в: develop и master
Соглашение о наименовании: hotfix-\*

#### Feature branches

Ветви функциональностей (feature branches) обычно существуют в репозиториях разработчиков (origin), но не в главном репозитории (upstream).
Соглашение о наименовании: всё, за исключением master, develop, release-_ или hotfix-_
Могут пораждаться от develop
Должны вливаться в develop

### Откат изменений

https://www.atlassian.com/ru/git/tutorials/undoing-changes

Локально:
Отменить индексирование (add): git reset <file>. Код не бэкапнется. Ещё можно git rm --cached <file> или -r . - удалить file или файлы рекурсивно из отслеживаемых. Несколько перечисляются через пробел
Откатить до индекса: git checkout <file>
Откатить до коммита: git restore
Удалить из индексирования и откатить до коммита всё и без вопросов: git reset . --quiet & git restore .
При pull, если необходимо отменить всё: git clean -f, ээфект такой же, как при git checkout другая_ветка --force, затем переключаемся обратно
Откат изменений до коммита либо к ветке, например master (полностью скачивает и заменяет коммиты, стерев историю, можно из upstream и т. д.): git reset --hard id либо origin/master

Название коммита: Как изменить название последнего локального коммита либо внести в него изменения? git commit --amend -m ""
Удалить ветку: git branch -d <branch>

Remote:
Удалить ветку: git push <remote_name> <branch> --delete

Локально и remote:
Откатить до коммита с удалением истории. Использовать в своей репе и ветке. В upstream убедиться, что удалённые коммиты уже не скачаны остальными: git reset --hard id & git push --force
Удалить все коммиты, включая самый первый: git update-ref -d HEAD, затем всё коммитим и git push --force
Откатить файлы к коммиту, сохранив историю, как если бы скачали коммит и этими файлами заменили свои: git restore --source <id_коммита> <file> & git push

### Vim, Vi

Вирусный редактор текста, работать в английской раскладке
https://youtu.be/6H0GDM8ExB8
esc - переход в командный режим
i - переход в режим редактирования текста
esc, Shift + Z два раза - сохранить и выйти, работать в английской раскладке
esc, Shift + ; пишем :q! - выйти без сохранения

## JavaScript

### JavaScript

`#JavaScript #JS`

Текст

### ECMAScript

`#ECMAScript #ES`

Текст

## Test

Текст
