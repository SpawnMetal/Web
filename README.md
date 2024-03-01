# Web Notes

- [Use](#Use)
- [JavaScript](#JavaScript)
  - [ECMAScript](#ECMAScript)
    - [JS 2021](#js-2021)
    - [EventLoop](#EventLoop)
      - [Стек](#Стек)
      - [Очередь](#Очередь)
      - [Куча](#Куча)
    - [Микрозадачи, Макрозадачи](#Микрозадачи-Макрозадачи)
    - [Hint](#Hint)
  - [Типы данных](#Типы-данных)
    - [Number](#Number)
    - [BigInt](#BigInt)
    - [String](#String)
    - [null](#null)
    - [Object](#Object)
      - [Клонирование объектов](#Клонирование-объектов)
      - [Слабые ссылки](#Слабые-ссылки)
    - [Symbol](#Symbol)
    - [Map, Set, WeakMap, WeakSet](#Map-Set-WeakMap-WeakSet)
    - [Иммутабельность](#Иммутабельность)
  - [Контекст](#Контекст)
    - [this](#this)
    - [Лексическое окружение](#Лексическое-окружение)
    - [Scope](#Scope)
      - [Порождающий контекст](#Порождающий-контекст)
      - [Связный список](#Связный-список)
    - [Замыкание](#Замыкание)
      - [Свободная переменная](#Свободная-переменная)
  - [Классы](#Классы)
    - [public](#public)
    - [static](#static)
    - [protected](#protected)
    - [private](#private)
    - [#abstract](#abstract)
    - [super](#super)
    - [implements](#implements)
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
    - [spread, rest](#spread-rest)
    - [Клонирование объектов](#Клонирование-объектов)
  - [Тернарный оператор](#Тернарный-оператор)
  - [Динамический ключ](#Динамический-ключ)
  - [Прототипы](#Прототипы)
  - [Операторы](#Операторы)
  - [Чистая функция](#Чистая-функция)
  - [freeze](#freeze)
  - [Дескрипторы](#Дескрипторы)
    - [get, set](#get-set)
  - [Reflect](#Reflect)
  - [Proxy](#Proxy)
  - [IIFE](#IIFE)
  - [??](#??)
  - [?.](#?.)
  - [new](#new)
    - [Instance](#Instance)
    - [new Function](#new-Function)
  - [delete](#delete)
  - [reduce](#reduce)
  - [for](#for)
    - [of](#of)
    - [in](#in)
  - [Регулярные выражения](#Регулярные-выражения)
- [Git](#Git)
- [Technology](#Technology)
  - [React](#React)
    - [Жизненный цикл](#Жизненный-цикл)
    - [Хук](#Хук)
      - [useState](#useState)
      - [useEffect](#useEffect)
      - [useLayoutEffect](#useLayoutEffect)
      - [useContext](#useContext)
      - [useMemo](#useMemo)
      - [useCallback](#useCallback)
      - [useRef](#useRef)
    - [memo](#memo)
    - [JSX](#JSX)
    - [Throttle и Debounce](#Throttle-и-Debounce)
    - [React Router](#React-Router)
    - [React DevTools](#React-DevTools)
    - [React Native](#React-Native)
  - [NestJS](#NestJS)
    - [Injectable](#Injectable)
    - [Injection scopes](#Injection-scopes)
    - [AdminJS](#AdminJS)
  - [Node.js](#Node.js)
    - [npm](#npm)
    - [npx](#npx)
  - [Express](#Express)
  - [GraphQL](#GraphQL)
  - [TypeORM](#TypeORM)
  - [Next.js](#Next.js)
  - [Babel](#Babel)
  - [Material Design](#Material-Design)
    - [Material UI](#Material-UI)
    - [Materialize](#Materialize)
    - [Material Design Lite](#Material-Design-Lite)
    - [Bootstrap Material Theme](#Bootstrap-Material-Theme)
  - [Axios](#Axios)
  - [Lodash](#Lodash)
  - [Webpack](#Webpack)
  - [esbuild](#esbuild)
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
  - [Монорепозитории](#Монорепозитории)
    - [Nx](#Nx)
    - [Lerna](#Lerna)
  - [Meteor](#Meteor)
  - [WebSocket](#WebSocket)
    - [Socket.IO](#SocketIO)
  - [Контейнеризация](#Контейнеризация)
    - [Docker](#Docker)
  - [Оркестрация](#Оркестрация)
    - [Kubernetes](#Kubernetes)
    - [OpenShift](#OpenShift)
    - [Docker Swarm](#Docker-Swarm)
    - [Portainer](#Portainer)
    - [Atlassian Compass](#Atlassian-Compass)
  - [Markdown](#Markdown)
  - [JSDoc](#JSDoc)
  - [Инструменты CI CD](#Инструменты-CI-CD)
    - [Jenkins](#Jenkins)
    - [Bamboo](#Bamboo)
    - [TeamCity](#TeamCity)
    - [CircleCI](#CircleCI)
    - [GitLab CI CD](#GitLab-CI-CD)
  - [pandas](#pandas)
- [Flux-архитектура](#Flux-архитектура)
  - [MobX](#MobX)
  - [Redux](#Redux)
  - [Effector](#Effector)
- [Принципы](#Принципы)
  - [Принципы, схемы и подходы программирования](#Принципы-схемы-и-подходы-программирования)
    - [Соглашения JavaScript](#Соглашения-JavaScript)
    - [MVC](#MVC)
      - [Модель](#Модель)
      - [Представление](#Представление)
      - [Контроллер](#Контроллер)
    - [SOLID](#SOLID)
    - [KISS](#KISS)
    - [DRY](#DRY)
    - [YAGNI](#YAGNI)
    - [Паттерны проектирования](#Паттерны-проектирования)
  - [Процесс разработки программного обеспечения, Жизненный цикл, MVP](#Процесс-разработки-программного-обеспечения-Жизненный-цикл-MVP)
  - [Реактивное программирование](#Реактивное-программирование)
  - [SaaS](#SaaS)
- [Typescript](#Typescript)
  - [enum](#enum)
  - [Generics](#Generics)
- [API](#API)
  - [REST, Open API](#REST-Open-API)
  - [Swagger](#Swagger)
- [NoSQL](#NoSQL)
  - [MongoDB](#MongoDB)
  - [Redis](#Redis)
  - [Firebase](#Firebase)
- [Браузер](#Браузер)
  - [Web Performance, Производительность, Рендер](#Web-Performance-Производительность-Рендер)
    - [Критические этапы рендеринга](#Критические-этапы-рендеринга)
      - [Этапы рендера](#Этапы-рендера)
    - [Lazy loading](#Lazy-loading)
  - [Сеть](#Сеть)
    - [MTLS](#MTLS)
    - [HTTP](#HTTP)
- [Автотесты](#Автотесты)
  - [Виды тестирования](#Виды-тестирования)
  - [Принципы тестирования](#Принципы-тестирования)
  - [Jest](#Jest)
- [IDE](#IDE)
  - [VSCode](#VSCode)
    - [Сниппеты VSCode](#Сниппеты-VSCode)
    - [Расширения VSCode](#Расширения-VSCode)
  - [WebStorm](#WebStorm)
- [Stacks](#Stacks)
  - [MERN](#MERN)
- [Генератор документации](#Генератор-документации)
- [Облачные сервисы](#Облачные-сервисы)
- [Транспиляция](#Транспиляция)
- [Cookie](#Cookie)
- [Определения](#Определения)
  - [Нативный](#Нативный)
  - [Адаптивность, Отзывчивость](#Адаптивность-Отзывчивость)
  - [Accessibility](#Accessibility)
  - [Семантика](#Семантика)
  - [Layout](#Layout)
  - [Legacy code](#Legacy-code)
  - [Миксин](#Миксин)
  - [Палиндром](#Палиндром)
  - [Сборка мусора](#Сборка-мусора)
  - [Веб-безопасность](#Веб-безопасность)
  - [Полифил](#Полифил)
  - [Микросервис](#Микросервис)
  - [SSR](#SSR)
  - [SEO](#SEO)
  - [Developer vs Engineer vs Architect](#Developer-vs-Engineer-vs-Architect)
  - [CI CD](#CI-CD)
  - [UX UI](#UX-UI)
  - [Артефакт, билд](#Артефакт-билд)
  - [Деплой](#Деплой)
  - [Tree shaking](#Tree-shaking)
- [HTML](#HTML)
- [CSS](#CSS)
  - [Селекторы](#Селекторы)
  - [Веса CSS](#Веса-CSS)
  - [Свойства](#Свойства)
  - [Flex](#flex)
  - [margin](#margin)
  - [SASS, SCSS](#SASS-SCSS)
  - [LESS](#LESS)
  - [БЭМ](#БЭМ)
- [Шрифты](#Шрифты)
- [Алгоритмы и структуры данных](#Алгоритмы-и-структуры-данных)
  - [Bubble](#Bubble)
  - [Selection](#Selection)
  - [Insertion](#Insertion)
  - [Merge](#Merge)
  - [Quick](#Quick)
- [Брокер](#Брокер)
  - [RabbitMQ](#RabbitMQ)
  - [NATS](#NATS)

## Use

- [Соглашения JavaScript](#Соглашения-JavaScript)
- [React](#React)
- [MobX](#MobX)
- [NestJS](#NestJS)
- [TypeORM](#TypeORM)
- [GraphQL](#GraphQL)
- [Swagger](#Swagger)
- [NoSQL](#NoSQL)
- [Typescript](#Typescript)
- [Jest](#Jest)
- [Git](#Git)
- [MVC](#MVC)
- [Material Design](#Material-Design)
- [WebSocket](#WebSocket), [Socket.IO](#SocketIO)
- [Docker](#Docker)
- [Jenkins](#Jenkins)
- [OpenShift](#OpenShift)
- [SASS, SCSS](#SASS-SCSS)
- [VSCode](#VSCode)
- [Markdown](#Markdown)
- [JSDoc](#JSDoc)
- [БЭМ](#БЭМ)

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

#clone: git clone \<remote_url\> - скопировать содержимое проекта. В текущую папку git clone \<remote_url\> . - с точкой вконце, скопирует содержимое в корень текущей директории, не создавая папку. Команда создаёт скрытую системную папку ".git" и делает git add origin

git init - инициализация проекта. Команда создаёт скрытую системную папку ".git"

git remote add \<remote_name\> \<remote_url\> - привязать проект remote_url к названию remote_name. Не ветке, просто названию, чтобы не писать длинную ссылку постоянно. Например remote_name = origin

git remote show \<remote_name\> - показать информацию об удалённом репозитории, ветке, HEAD и т д

git remote -v - покажет все добавленные remote_url и их remote_name

git remote rm \<remote_name\> - удалить привязку remote_name к remote_url из списка

git remote set-url \<remote_name\> \<remote_url\> - изменить remote_url

### Комбо

#Персональные данные: git config --global user.name "name" & git config --global user.email "email" & git config --global http.sslverify false

Init & GitHub: git init & git add . & git commit -m "First commit" & git branch -M main & git remote add origin https://github.com/SpawnMetal/lib.git & git push -u origin main

#Файлы Update: git add . & git commit -m "Updated date" & git push

#Файлы Синхронизация: git add . & git commit -m "" & git pull origin \<branch\> & git push

#Ветки Удаление ветки: git checkout develop & git branch -d \<branch\> & git push \<remote_name\> \<branch\> --delete

### Файлы

git push -u \<remote_name\> \<branch\> - Заливает новую branch в remote_name. Создаёт pull request, если ветка уже есть. -u -это upstream, мол сервер. Например выполнив команду git push -u origin master вы устанавливаете связь между той веткой, в которой вы находитесь и веткой master на удалённом сервере. Команду требуется выполнить единожды, чтобы потом можно было отправлять/принимать изменения лишь выполняя git push из ветки без указания всяких алиасов для сервера и удалённых веток. Это сделано для удобства.

git push - залить в текущую ветку на сервер, ранее должна быть установлена связь git push -u

git push \<remote_name\> \<branch\> - заливает изменения по \<remote_name\> в \<branch\>

Флаг --force отменяет необходимость в pull и подгоняет ветку удаленного репозитория под вашу локальную ветку, удаляя любые вышестоящие изменения, которые могли быть внесены с момента последнего выполнения вами команды pull.

git pull \<remote_name\> \<branch\> - шоткод для команд git fetch и git merge. \<remote_name\> и \<branch\> по умолчанию текущие. Получит с сервера и объединит с локальной.
При работе с fork не забывать пуллить свою форку с remote.

--rebase либо git rebase - Перебазирует ветку на текущий и дальнейшие коммиты, которые будут попадать в историю коммитов (например master) на момент её слияния с перебазированной веткой (develop), а не на момент создания коммита в прошлом.
Т.е. коммит сделанный 3 года назад в develop, при слиянии попадёт в самый верх коммитов master. См. Commits on Jun 22, 2022 https://github.com/SpawnMetal/examples/commits/master
Использовать при пулле из upstream в origin https://www.atlassian.com/ru/git/tutorials/syncing/git-pull

git rebase --skip позволит пропустить конфликт при git rebase, для каждого конфликта команда вводится отдельно

git add \<file\> или . - добавляет file или все файлы в отслеживаемые для добавления в коммит. Несколько перечисляются через пробел.

git fetch \<remote_name\> \<branch\> - получить изменения, но не делать слияние - git merge.

git merge \<branch\> - объединить скачанные изменения с текущей веткой, либо branch, если указана, в таком случае из branch будут получены все изменения

git commit -m \<text\> - зафиксировать отслеживаемые файлы, создав коммит. -m = -message. text указывается в двойных кавычках. После ввода команды будет выведен хэш коммита

git show \<id\> просмотр информации о теге, коммите, ветке

git status - показать текущую ветку и изменённые файлы

git clone см #clone

git checkout \<id\>, \<file\> либо \<tag\> - переключиться на id коммита, tag либо откатить файл до индекса. Работает с тремя различными объектами: файлами, коммитами и ветками. Команда открепляет HEAD, что не позволит сохранить изменения при неизбежном переключении обратно в ветку.

Удалить индексы, не файлы, код не бэкапнется. Несколько файлов перечисляются через пробел:
git reset \<file\>

git rm --cached \<file\>

git rm -r .

git reset --hard id либо origin/master - откатит код до коммита id либо ветки origin/master, стерев историю

git restore \<file\> - откатит до коммита (бэкапнет код) не проиндексированные файлы, проиндексированные сначала отменить: git reset \<file\>

git restore --source \<id_коммита\> \<file\> - откатит код до коммита id сохранив историю, создав новый коммит

git show \<commit_id\> - покажет информацию о коммите и его полный id

git commit --amend -m "" - переименовать либо отредактировать текст последнего коммита

git log -кол-во --pretty=oneline - покажет информацию по кол-ву последних коммитов, теги, сообщения коммитов, HEAD. Напротив последней залитой будет красным написано origin/branch

get tag -a - аннотированный тег, некое название коммита https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository/git-tag https://git-scm.com/book/ru/v2/Основы-Git-Работа-с-метками

git tag -a v1.0.1 -m "" - создать тег

git tag -a -f \<tag\> -m "" \<id\> - переименовать тег у коммита id

git tag -a \<tag\> \<id\> - задать тег любому коммиту id

git tag - просмотр списка тегов

git show \<tag\> просмотр информации о теге, коммите, ветке

git tag -d \<tag\> - удалить тег

git stash - сохраняет данные, чтобы можно было переключиться на другую ветку не делая пока коммит https://www.atlassian.com/ru/git/tutorials/saving-changes/git-stash

git stash list - просмотр всех stash

git stash apply n - откатить к последнему, где n временный коммит, не обязательный параметр. git add . - застешать несколько

### Ветки

git branch - выводит список веток и ветку в которой я нахожусь. В VSCode слева снизу

git branch \<branch\> - создаст ветку name, копию текущей

git branch -d \<branch\> - удалит ветку name локально. Необходимо сначала переключиться на другую. -D, если необходимо удалить принудительно (--force)

git pull origin develop - скачать новую ветку с сервера

git push \<remote_name\> \<branch\> --delete - удаляет ветку на сервере

git branch -m \<branch\> - переименовать текущую ветку в name, -M, если необходимо переименовать, даже если такая ветка уже сушествует

git checkout \<branch\> - переключиться на ветку name

git checkout -b \<branch\> - создать и переключиться на ветку name, копию текущей

git checkout -b \<branch\> \<remote_name\> - создать и переключиться на ветку branch, ответвление от name_from

git checkout -b \<branch\> \<repository_name_from\>/\<branch\> - скопировать удалённую ветку и переключиться в неё

git push -u \<remote_name\> \<branch\> - Заливает НОВУЮ!!! branch в remote_name. Создаёт pull request при необходимости. -u: upstream. remote_name: название ссылки, которое устанавливал с помощью git remote add \<remote_name\> \<remote_url\>. branch: ветка, которую будем заливать.

git show \<branch\> просмотр информации о теге, коммите, ветке

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

Отменить индексирование (add): git reset \<file\>. Код не бэкапнется. Ещё можно git rm --cached \<file\> или -r . - удалить file или файлы рекурсивно из отслеживаемых. Несколько перечисляются через пробел

Откатить до индекса: git checkout \<file\>

Откатить до коммита: git restore

Удалить из индексирования и откатить до коммита всё и без вопросов: git reset . --quiet & git restore .

При pull, если необходимо отменить всё: git clean -f, ээфект такой же, как при git checkout другая_ветка --force, затем переключаемся обратно

Откат изменений до коммита либо к ветке, например master (полностью скачивает и заменяет коммиты, стерев историю, можно из upstream и т. д.): git reset --hard id либо origin/\<branch\>

Название коммита: Как изменить название последнего локального коммита либо внести в него изменения? git commit --amend -m ""

Удалить ветку: git branch -d \<branch\>

По новой скачать всё из ветки: git fetch origin \<branch\> & git reset --hard origin/\<branch\> - сначала скачает всё (fetch), затем откатит всё к скаченным данным (reset)

Remote:

Удалить ветку: git push \<remote_name\> \<branch\> --delete

Локально и remote:

Откатить до коммита с удалением истории. Использовать в своей репе и ветке. В upstream убедиться, что удалённые коммиты уже не скачаны остальными: git reset --hard id & git push --force

Удалить все коммиты, включая самый первый: git update-ref -d HEAD, затем всё коммитим и git push --force

Откатить файлы к коммиту, сохранив историю, как если бы скачали коммит и этими файлами заменили свои: git restore --source \<id_коммита\> \<file\> & git push

### Vim, Vi

Вирусный редактор текста, работать в английской раскладке

https://youtu.be/6H0GDM8ExB8

esc - переход в командный режим

i - переход в режим редактирования текста

esc, Shift + Z два раза - сохранить и выйти, работать в английской раскладке

esc, Shift + ; пишем :q! - выйти без сохранения

## JavaScript

`#JavaScript #JS`

JavaScript - Мультипарадигменный (расширяемый и использующий другие языки) язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили. Является реализацией языка ECMAScript. В него конвертируются: TypeScript, CoffeeScript, Flow, Dart.

JavaScript работает в одном потоке, поэтому об асинхронности не может быть речи, event loop и call stack сделали асинхронность возможной (сторонние API).

JavaScript интерпретируемый язык - выполняется сразу, в отличае от компиляции

### JS 2021

Конструкции наподобие a && (a = b) теперь можно записывать как a &&= b, a ||= b, a ??= b
Числа можно отделять с помощью \_, не влияя на их структуру 1000000000 === 1_000_000_000

### EventLoop

`#EventLoop`

https://tproger.ru/translations/upravlenie-pamjatju-v-javascript/#:~:text=%D0%9A%D1%83%D1%87%D0%B0%20(%D0%B0%D0%BD%D0%B3%D0%BB.,%D0%B2%D1%8B%D0%B4%D0%B5%D0%BB%D1%8F%D0%B5%D1%82%20%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C%20%D0%BF%D0%BE%20%D0%BC%D0%B5%D1%80%D0%B5%20%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8.
https://developer.mozilla.org/ru/docs/Web/JavaScript/EventLoop

https://youtu.be/8aGhZQkoFbQ?t=773

Параллелизм/Многопоточность в JavaScript работает за счёт цикла событий (event loop), который отвечает за выполнение кода, сбора и обработки событий и выполнения подзадач из очереди (queued sub-tasks).

В JavaScript есть два варианта хранения данных: в `стеке` и в `куче`; и то, и другое – названия `структур данных`, которые используются движком для различных целей.

#### Стек

`#Stack #Стек`

`Стек (англ. stack)` – это структура данных, которая используется для хранения статических данных, т.е. тех, чей размер известен во время компиляции. В JavaScript сюда включаются примитивные значения (string, number, boolean, undefined и null) и ссылки на функции и объекты.

Процесс `выделения памяти` прямо перед выполнением называется `статическим`.

Вызов любой функции создаёт контекст выполнения (Execution Context). При вызове вложенной функции создаётся новый контекст, а старый сохраняется в специальной структуре данных - стеке вызовов (Call Stack).

#### Очередь

`#Queue #Очередь`

Среда выполнения JavaScript содержит `очередь задач`. Эта очередь — список задач, подлежащих обработке. Каждая задача ассоциируется с некоторой функцией, которая будет вызвана, чтобы обработать эту задачу.
Когда стек полностью освобождается, самая первая задача извлекается из очереди и обрабатывается. Обработка задачи состоит в вызове ассоциированной с ней функции с параметрами, записанными в этой задаче. Как обычно, вызов функции создаёт новый контекст выполнения и заносится в стек вызовов.
Обработка задачи заканчивается, когда стек снова становится пустым. Следующая задача извлекается из очереди и начинается её обработка.

#### Куча

`#Heap #Куча`

`Куча (англ. memory heap)` используется для хранения таких данных, как объекты и функции.

В отличие от случая со стеком, движок не знает, какой объем памяти понадобится для тех или иных объектов, а потому выделяет память по мере необходимости.

Такое `выделение памяти` называют `динамическим`.

### Микрозадачи, Макрозадачи

`#Микро #Макро #Микрозадачи #Макрозадачи`

https://learn.javascript.ru/event-loop

https://habr.com/ru/post/264993/

https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/#why-this-happens

Порядок, сначала выполняются микрозадачи в рамках макрозадачи, затем очередь микрозадач:

- МАкрозадача
  - МИкрозадачИ
    - Очередь мИкрозадач
    - Очередь мАкрозадач

Может так случиться, что задача поступает, когда движок занят чем-то другим, тогда она ставится в очередь.

Очередь, которую формируют такие задачи, называют «очередью макрозадач» (macrotask queue, термин v8).

Вызов .then(func) у решённого промиса немедленно ставит в очередь микрозадачу. Вот почему promise1 и promise2 выводятся в журнал после script end, ведь текущий исполняемый сценарий должен завершиться до того как начнут обрабатываться микрозадачи. promise1 и promise2 выводятся в журнал до setTimeout ибо микрозадачи всегда развёртываются до следующей большой задачи.

Итого:

Сначала выполняются микрозадачи

setTimeout ставит в очередь большую задачу

promise ставит в очередь микрозадачу

В мире ECMAScript микрозадачи именуют заданиями («jobs»).

Если мы хотим запустить функцию асинхронно (после текущего кода), но до отображения изменений и до новых событий, то можем запланировать это через queueMicrotask.

Поэтому queueMicrotask можно использовать для асинхронного выполнения функции в том же состоянии окружения.

### Hint

`#Преобразование #Примитивы #Хинт #Hint`

Преобразование объектов в примитивы https://learn.javascript.ru/object-toprimitive

В отсутствие Symbol.toPrimitive и valueOf, toString обработает все примитивные преобразования.

Сначала вызывается метод obj[Symbol.toPrimitive](hint), если он существует,

В случае, если хинт равен "string" происходит попытка вызвать obj.toString() и obj.valueOf(), смотря что есть.

В случае, если хинт равен "number" или "default" происходит попытка вызвать obj.valueOf() и obj.toString(), смотря что есть.

Все эти методы должны возвращать примитив (если определены).

### ECMAScript

`#ECMAScript #ES`

ECMAScript (ES, European Computer Manufacturers Association) - это встраиваемый расширяемый не имеющий средств ввода-вывода язык программирования, используемый в качестве основы для построения других скриптовых языков.

Расширения (реализации) языка: JavaScript, JScript, ActionScript, SpiderMonkey, V8.

ES6-8 https://youtu.be/Ti2Q4sQkNdU

ES2020 / JS2020 https://youtu.be/7TpAN4FISeI

### IIFE

`#IIFE`

https://developer.mozilla.org/ru/docs/Glossary/IIFE

IIFE (Immediately Invoked Functional Expression, немедленно вызываемое функциональное выражение). (function(){тело})(собачьи яйца)

Является одной из немногих исключительных ситуаций, перед которой ставится точка с запятой

### Классы

`#Классы #Classes`

https://youtu.be/uLY9GXGMXaA

https://learn.javascript.ru/es-class

Классы - это синтаксический сахар для более удобного создания объектов, наследования и прототипирования

В js 2021 можно сделать приватным поле либо метод с помощью #. #id - будет приватным. `#Решётка #Приватность`

Порядок инициализации https://www.typescriptlang.org/docs/handbook/2/classes.html#initialization-order

#### public

`#public`

https://www.typescriptlang.org/docs/handbook/2/classes.html#public

Обращаемся к методам из инсты

```ts
class Greeter {
  public greet() {
    console.log('hi!')
  }
}
const g = new Greeter()
g.greet()
```

#### static

`#static`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Classes/static

https://www.typescriptlang.org/docs/handbook/2/classes.html#static-members

static - объявление внутри класса, наследуется, но не появляется у присвоенных значений, например class Cl, обращение будет Cl.fn(), а не const cl = new Cl(), cl.fn(), в public наоборот только у инсты обращаемся

Также статические поля и методы могут наследоваться, что позволяет обращаться к ним через имя производного класса: Class1 extends Class2, Class1.methodClass2()

#### protected

`#protected`

https://www.typescriptlang.org/docs/handbook/2/classes.html#protected

Обращение возможно только из собственного и дочерних классов, изнутри, не из инсты

#### private

`#private`

https://www.typescriptlang.org/docs/handbook/2/classes.html#private

Доступ возможен только из самого класса, из подклассов и инсты нельзя, но ошибку выдаст только ts, сам js выполнится

#### abstract

`#abstract`

https://www.typescriptlang.org/docs/handbook/2/classes.html#abstract-classes-and-members

Означает, что в родительском abstract классе есть только объявления свойств и методов, а наполнение происходит в подклассах

#### super

`#super`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/super

Ключевое слово super используется для вызова конструктора родителя, также может быть использовано для вызова функций родительского объекта.

#### implements

`#implements`

https://www.typescriptlang.org/docs/handbook/2/classes.html

implements необходим, чтобы проверить, удовлетворяет ли класс определенному interface. Будет выдано сообщение об ошибке, если класс не сможет правильно его реализовать:

```ts
interface Pingable {
  ping(): void;
}

class Sonar implements Pingable {
  ping() {
    console.log("ping!");
  }
}

class Ball implements Pingable {
Class 'Ball' incorrectly implements interface 'Pingable'.
  // Property 'ping' is missing in type 'Ball' but required in type 'Pingable'.
  pong() {
    console.log("pong!");
  }
}
```

### Контекст

`#Контекст (Контекст выполнения) #Context (execution context))`

http://old.code.mu/books/javascript/context/prodvinutaya-rabota-s-kontekstom-v-javascript.html

https://habr.com/ru/post/468943/

Пример examples\context.js region ContextNewExample https://github.com/SpawnMetal/examples

Контекст выполнения (execution context) — это, если говорить упрощённо, концепция, описывающая окружение, в котором производится выполнение кода на JavaScript. Код всегда выполняется внутри некоего контекста.

Карта:

```
ObjectOver / FunctionOver
{
  Object / Function
  { Scope // Свойство функции, а не контекста. В Scope записывается вся иерархия LexicalEnvironment
    const a = 'text';

    { Scope2
      const b = 'text';
    }

    LexicalEnvironment: // Лексическое окружение. Наполнение словаря происходит при объявлении
    {
      this: Object / Function // Ссылка на контекст выполнения, доступно только при выполнении
      ScopeChain: // Лексическая цепочка. Связь с пораждающими контекстами. Спецификация утверждает, что ScopeChain это массив
      [
        LE: {
          Scope: {
            a: 'text',
            Scope2: {
              b: 'text',
              LE.prototype, // Также не стоит забывать, что если у какого-то из звеньев в цепи ScopeChain есть прототип, то поиск будет осуществляться и в прототипе тоже
            }
          }
        },
        LE.ObjectOver,
        LE1,
        LE2,
        ...,
        LEglobal
      ]
    }
  }
}
```

#### this

`#this`

`this` — это связь сущности с контекстом исполнения, с порождающим контекстом(ScopeChain).

Самое важное, что нужно понять о `this`, заключается в том, что у функций нет фиксированного значения `this`. Это значение зависит от того, как именно вызывается функция. Если мы говорим о том, что функция вызывается с некоторым конкретным значением `this`, это значит, что это значение определяется не во время объявления функции, а во время её вызова. Вот некоторые особенности `this`:

- Если функция вызывается в `обычном виде` (то есть, с использованием конструкции вида someFunc()), то `this` будет ссылаться на `глобальный объект` (в браузере это window). Если код выполняется в `строгом режиме (strict mode)`, то в `this` будет записано значение `undefined`.
- Если функция вызывается как `не стрелочный метод объекта`, то ключевое слово `this` будет представлено `объектом`, которому принадлежит метод.
- Если функцию вызывают с использованием `call` или `apply`, `this` будет представлено тем, что указано в качестве `первого аргумента`. Функции, созданные с использованием `bind`, имеют `иммутабельное` значение `this`.
- Если функция вызывается в виде `обработчика события`, то в `this` будет `целевой элемент события`.
- Если функцию вызывают в виде `конструктора`, с использованием ключевого слова `new`, то в `this` будет `новый объект`, прототип которого установлен в качестве свойства `prototype функции-конструктора`.
- `this и ScopeChain` — это свойства контекста исполнения, но `this` никак не сам контекст.
- `#Стрелочные функции` не создают свой контекст. `call` не поможет. Можно получить `замкнутый this`, а не контекст родителя, например obj1.obj2.arrow() в arrow не будет ссылаться на obj1.this, а например obj1.obj2.function(arrow()) будет. См пример вначале главы [Контекст](#Контекст)

- `#call` function.call(this, arg1, arg2...) - вызов функции с передачей контекста и аргументов через запятую https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Function/call
- `#apply` function.apply(this, [arg1, arg2...]) - то же, что и call, только аргументы передаются в массиве (обрабатываются через ...args) https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Function/apply
- `#bind` function.bind(this, arg1, arg2...)() - создание новой функции с переданным контекстом, аргументы передаются через запятую, bind присваивается переменной, затем она вызывается как функция. bind позволяет закрепить контекст, чтобы не произошла потеря контекста. bind нельзя применить повторно к забинденной функции https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Function/bind

`Потеря контекста`: https://learn.javascript.ru/bind

Когда мы привязываем аргументы, такая функция называется «частично применённой» или «частичной».

Частичное применение удобно, когда мы не хотим повторять один и тот же аргумент много раз. Например, если у нас есть функция send(from, to) и from всё время будет одинаков для нашей задачи, то мы можем создать частично применённую функцию и дальше работать с ней.

- Правило определения `this` для функций, вызванных обычным способом:

Если слева от скобок активации функции находится `ReferenceType`, то в `this` функции проставляется `base` этого `ReferenceType`. Если слева от скобок `любой другой тип`, то в `this` проставляется `глобальный объект` или `undefined`

```js
const x = 0

const obj = {
  x: 10,
  foo: function () {
    return this.x
  },
}

obj.foo() // Вернёт 10 т.к. слева от скобок ReferenceType свойство base которого указывает на объект obj

const test = obj.foo // Присвоим метод объекта в глобальную переменную

test() // Вернёт 0 т.к. вызов test() эквивалентен вызову ГО.test(), т.е. свойство base укажет на глобальный объект, а в глобальном объекте х присвоено 0
```

У типа `ReferenceType` есть встроенный метод `GetValue`, который `возвращает истинный тип` получаемого через `ReferenceType` объекта. В `зоне выражения` `GetValue` всегда `срабатывает`.

```js
;(function () {
  return this // this проставляется глобальный объект или undefined в зависимости от strict mode
})()
```

Это происходит из-за того, что в `зоне выражения` у нас всегда `срабатывает` `GetValue`. `GetValue` возвращает `тип Function` и `слева от скобок` активации получается `не ReferenceType`.

#### Лексическое окружение

`#LexicalEnvironment #Лексическое окружение #LE #ЛО #Динамическая область`

https://habr.com/ru/post/474852/

https://habr.com/ru/post/468943/

https://russianblogs.com/article/87531190106/

- `Лексическое окружение` — это `хранилище` для данных в памяти и `механизм для извлечения` этих данных при обращении.
- `Лексическая область` - определяется во время `написания` кода, тогда как `динамическая область` (и `this`) - во время `выполнения`. `Лексическая область` заботится о том, где была `объявлена` функция, а `динамическая область` - о том, откуда была `вызвана` функция.
- И наконец: `this` заботится о том, `как была вызвана функция`. Это показывает нам, насколько тесно механизм `this` связан с идеей `динамической области` видимости.

`Наполнение словаря` происходит при вызове функции, а не при определении.

```js
{
  const showWarning = field => {
    // LexicalEnvironment = { field: 'email' }
    const warning = `verify your ${field}, please`
    // LexicalEnvironment = { warning: 'verify your email, please', field: 'email' }
    console.log(warning)
  }

  showWarning('email') // => verify your email, please
}
```

- `Lexical Environment` — это тип спецификации, используемый для разрешения имён идентификаторов при поиске конкретных переменных и функций на основе лексической структуры вложенности кода ECMAScript.
  Лексическое окружение (Lexical Environment) состоит из записи среды и, возможно, нулевой ссылки на внешнюю Лексическую среду.

Технически ЛО представляет собой объект с двумя свойствами:

- запись окружения (именно тут хранятся все объявления)
- ссылка на ЛО порождающего контекста.

Своего рода `ScopeChain` у функций — это аналог `Лексического окружения`.

Лексическое окружение содержит в себе:

- все объявления переменных контекста
- все декларации функций
- все формальные параметры функции(если речь идёт о контексте функций)

#### Scope

`#Scope`

https://frontend-stuff.com/blog/javascript-introduction-to-scope

https://developer.mozilla.org/en-US/docs/Glossary/Scope

https://habr.com/ru/post/468943/

`Область видимости`, по сути есть локальная (внутри scope - SCOPE) и глобальная (доступ к данным из вне scope - ScopeChain) области.

Обратите внимание! `SCOPE` в отличии от ScopeChain является свойством самой функции, а не её контекста.

`SCOPE` — это свойство самой функции, содержит в себе иерархическую цепь лексических окружений порождающих контекстов.

`SCOPE` функций, создаваемых через new Function = ГО. См [new Function](#new-Function) и [new](#new)

Следствие – такие функции не могут использовать замыкание. Но это хорошо, так как бережёт от ошибок проектирования, да и при сжатии JavaScript проблем не будет. Если же внешние переменные реально нужны – их можно передать в качестве параметров.

{

Данная запись scope называется `block scope`

Переменные объявленные через `let` и `const` создаются внутри данного `scope` и при одинаковом названии в родителе и `дочернем scope`, будет меняться значение переменной объявленной в `текущем scope`

В `дочернем scope` возможно изменение значения уже объявленной переменной в родителе

}

##### Порождающий контекст

`#ScopeChain #Порождающий контекст #Цепь областей видимости`

https://habr.com/ru/post/468943/

`ScopeChain` — это связь сущности со всеми порождающими контекстами.

`ScopeChain` — это `LE` (лексическое окружение текущего контекста) + `SCOPE`

`this` и `ScopeChain` — это `свойства` контекста исполнения

`Цепь областей видимости` также является свойством контекста исполнения как и `this`. Она представляет собой список объектов лексических окружений текущего контекста и всех порождающих контекстов. Именно в этой цепи происходит поиск переменных при разрешении имён идентификаторов.

Обратите внимание: `this` связывает функцию с контекстом исполнения, а `ScopeChain` с порождающими контекстами.
Спецификация утверждает, что `ScopeChain` это массив:

`SC = [LO, LO1, LO2,..., LOglobal];`

Однако, в некоторых реализациях, например в JS, цепь областей видимости реализована через связанные списки.

Обратите внимание! `SCOPE` в отличии от `ScopeChain` являертся свойством самой функции, а не её контекста.

При вызове функции инициализируется и наполняется её контекст исполнения. Контексту проставляется `ScopeChain` = LO(самой функции) + `SCOPE`(иерархическая цепь LO пораждающих контекстов).

Важным исключением является функция-конструктор. Для этого типа функций `SCOPE` всегда указывает на глобальный объект.

Также не стоит забывать, что если у какого-то из звеньев в цепи `ScopeChain` есть прототип, то поиск будет осуществляться и в прототипе тоже.

##### Связный список

`#Связный список`

https://ru.wikipedia.org/wiki/%D0%A1%D0%B2%D1%8F%D0%B7%D0%BD%D1%8B%D0%B9_%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA

`Связный список` — базовая динамическая структура данных в информатике, состоящая из узлов, каждый из которых содержит как собственно данные, так и одну или две ссылки («связки») на следующий и/или предыдущий узел списка.

Принципиальным преимуществом перед массивом является структурная гибкость: порядок элементов связного списка может не совпадать с порядком расположения элементов данных в памяти компьютера, а порядок обхода списка всегда явно задаётся его внутренними связями.

`#Стек`

Если речь в контексте структуры данных, то это последовательный список элементов в информатике, например массив. Обслуживание самых новых событий, старые дольше висят.

`#Очередь`

Здесь удаляются самые старые данные. Тоесть сначала обслуживание самых первых событий в очереди.

#### Замыкание

`#Замыкание #Closures`

https://youtu.be/pahO5XjnfLA

`Замыкание` — совокупность блока кода и данных того контекста, в котором тот блок порождён, т.е. это связь сущности с порождающими контекстами через цепь ЛО или SсopeChain.

Проще говоря замыкание верхнеуровневого значения переменной в дочернем скоупе.

Как правило это возврат функции из функции, в верхнеуровневую подаётся значение аргумента, которое используется в возвращаемой функции без передачи в неё этого параметра

examples/closure.js https://github.com/SpawnMetal/examples

```js
function person() {
  let name = 'Peter'

  return function displayName() {
    console.log(name)
  }
}
let peter = person()
peter() // prints 'Peter'
```

##### Свободная переменная

`#Свободная переменная`

https://habr.com/ru/post/474852/
Свободная переменная — переменная, используемая функцией, но не являющаяся ни формальным параметром, ни локальной переменной для этой функции.

```js
function testFn() {
  var localVar = 10 // Свободная переменная для функции innerFn

  function innerFn(p) {
    alert(p + localVar)
  }

  return innerFn // Возврат функции
}

var test = testFn() // Присвоим innerFn в переменную
test() // В стековых языках это бы не работало
```

### Генераторы

`#Генераторы #Generator`

Генераторы – новый вид функций в современном JavaScript. Они отличаются от обычных тем, что могут приостанавливать своё выполнение, возвращать промежуточный результат и далее возобновлять его позже,
в произвольный момент времени.

https://learn.javascript.ru/generator

```js
function* generateSequence() {
  yield 1
  yield 2
  return 3
}
```

При запуске generateSequence() код такой функции не выполняется. Вместо этого она возвращает специальный объект, который как раз и называют «генератором».

Правильнее всего будет воспринимать генератор как «замороженный вызов функции».

При создании генератора код находится в начале своего выполнения.

Основным методом генератора является next(). При вызове он возобновляет выполнение кода до ближайшего ключевого слова yield. По достижении yield выполнение приостанавливается, а значение – возвращается во внешний код

«Открутить назад» завершившийся генератор нельзя, но можно создать новый ещё одним вызовом generateSequence() и выполнить его.

```js
let generator = generateSequence()
let one = generator.next() // {value: 1, done: false}
let two = generator.next() // {value: 2, done: false}
let three = generator.next() // {value: 3, done: true}
```

### Шаблонные литералы

`#Шаблонные литералы`
Шаблонными литералами называются строковые литералы, допускающие использование выражений внутри. С ними вы можете использовать многострочные литералы и строковую интерполяцию. В спецификациях до ES2015 они назывались "шаблонными строками".

```js
const str = `строка текста`

const str = `строка текста 1
  строка текста 2`

const str = `строка текста ${выражение} строка текста`

tag`строка текста ${выражение} строка текста`
```

### Promise

`#Promise`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Promise

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Using_promises

https://learn.javascript.ru/promise

Git https://github.com/domenic/promises-unwrapping/blob/master/docs/states-and-fates.md

Примеры:

- es/es-6-8/11_promises.js https://github.com/SpawnMetal/es-6-8
- es/es-2020/2_promises.js https://github.com/SpawnMetal/es-2020
- examples/microAndMacrotasks.js https://github.com/SpawnMetal/examples

Promise (промис) - это объект, представляющий результат успешного или неудачного завершения асинхронной операции. Так как большинство людей пользуются уже созданными промисами, это руководство начнём с объяснения использования вернувшихся промисов до объяснения принципов создания.

В сущности, промис - это возвращаемый объект, в который вы записываете два колбэка вместо того, чтобы передать их функции.

Объект Promise (промис) используется для отложенных и асинхронных вычислений.

Promice - это специальный объект, который содержит своё состояние. Вначале pending («ожидание»), затем – одно из: `fulfilled` («выполнено успешно») или `rejected` («выполнено с ошибкой»).

Промисы необходимы для организации асинхронного кода.

Функции:

- `all`: выполняет все промисы, если один выполнится с ошибкой, то вернётся ошибка. Возвращает массив результатаов
- `allSettled`: выполняет все промисы. Возвращает массив объектов { status: 'fulfilled', value: 1 }
- `race`: ждёт только первый выполненный промис
- `any`: ждёт только первый успешно выполненный промис
- `resolve`: then
- `reject`: catch

```js
const promise = new Promise(function (resolve, reject) {
  // Эта функция будет вызвана мгновенно

  // В ней можно делать любые асинхронные операции,
  // А когда они завершатся — нужно вызвать одно из:
  // resolve(результат) при успешном выполнении. Вызывается 1 раз, второй вызов будет проигнорирован
  // reject(ошибка) при ошибке. Вызывается 1 раз, второй вызов будет проигнорирован

  setTimeout(() => {
    if (data) resolve(data) // promise.then
    else reject(new Error('error')) // promise.catch
  })
})
```

Промисификация – создание асинхронной обёртки для синхронной функции, возвращающую промис работы синхронной.

Чейнинг – последовательный вызов promise.then(...).then(...).then(...).catch(...).catch(...)

### Код

`#Код`

https://youtu.be/Ti2Q4sQkNdU https://github.com/SpawnMetal/es-6-8

- #Константы #let #const es/es-6-8/1_let_const.js
- #Стрелочные #лямбда функции es/es-6-8/2_arrow_functions.js
- Параметры по умолчанию es/es-6-8/3_default_params.js
- #Строки #string es/es-6-8/4_strings.js
- Рест и спреад es/es-6-8/5_rest_spread.js
- Объекты es/es-6-8/6_objects.js
- Модули es/es-6-8/7_modules/module.js
- #Классы #Classes es/es-6-8/8_classes.js examples/classes.js
- #Символы #Symbol es/es-6-8/9_symbols.js
- Генераторы es/es-6-8/10_generators.js
- Промисы es/es-6-8/11_promises es/es-2020/2_promises.js
- Мап и сет es/es-6-8/12_map_set.js
- Рефлект es/es-6-8/13_reflect.js patterns/2 structural/9_proxy.js
- Прокси es/es-6-8/14_proxy.js

---

- #Замыкания #Closures examples/closure.js https://github.com/SpawnMetal/examples
- #Контекст #Context examples/context.js region ContextNewExample https://github.com/SpawnMetal/examples
- Примеры examples/example.js https://github.com/SpawnMetal/examples
- #MVC examples/mvc.js https://github.com/SpawnMetal/examples
- #Импорты #Imports es/es-2020/1_imports.js https://github.com/SpawnMetal/es-2020
- #?? #Nullable es/es-2020/3_nullable.js https://github.com/SpawnMetal/es-2020
- #?. #Optional es/es-2020/4_optional.js https://github.com/SpawnMetal/es-2020

---

- `async`: вернёт Promise, хорошая практика обработки в теле async функции с помощью try catch
- `await`: заставляет ждать Promise, выполнение функции, а затем продолжает код
- `for...of`: то же, что и for...in, только в in цикл по ключу (for key in obj), а в of по значению (for val of obj), таким образом можно по циклу вызывать функцию сразу либо присваивать новое значение value, без obj['key']
- `static`: позволит обратиться к свойству либо методу класса без запуска конструктора
- `export default`: запускает функцию по умолчанию при импорте модуля. Например импорт класса из модуля: const Person = module.default
- `globalThis`: это стандартизированный window / global и т. д. для всех платформ
- `??`: это || за исключением того, что нормальные типизированные значения считает приемлемыми, например false || 'default false' = false
- `?.`: проверка на существование, например свойства объекта или DOM элемента. key1?.key2?.key3 либо document.querySelector('div')?, массив: key1?.key2?.[id], функция: key1?.key2?.func.?()
- `|>`: pipeline operator, передаёт в следующую функцию результат выполнения предыдущей: func1(func2(func3('qwe'))) = 'qwe' |> func3 |> func2 |> func1;
- `function* FunctionName()`: функция-генератор, yield - пошаговый return на котором функция приостанавливает выполнение и возвращает это значение, если функция будет вызвана заново, то она продолжит выполнение после yield
- Boolean([] {} function(){}) = true
- `===` сравнивает без приведения типов, а `==` с приведением

### Прототипы

`#Prototype #Прототипы`

prototype добавляет методы к инсте, а не к самому классу, но обратиться к методу можно через Class.prototype.method. Получается он работает только с this - контекстом выполнения и используется только при выполнении и не применим к самому классу, так как this должен содержать значение с которым мы работаем, например массив

Каждый объект имеет прототип от наследуемого `__proto__`. В ES5 Object.getPrototypeOf()

Через свойство prototype можно добавлять и изменять параметры

prototype - прототип текущего класса, а `__proto__` - родительского

Например, Object.prototype существует, а obj = {}, obj.prototype не существует. Object.prototype === obj.`__proto__`

Создать прототип у newObj = Object.create(proto, {{a: 'text'}}). Пример: "patterns\1 creational\3_prototype.js" https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/create

Либо Object.setPrototypeOf(obj, constructor.prototype) Пример: "examples\example.js" https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/setPrototypeOf

### Операторы

`#Операторы`
Эта глава описывает выражения и операторы языка JavaScript, такие как операторы присваивания, сравнения, арифметические, битовые, логические, строчные, и различные специальные операторы. https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Expressions_and_Operators

Эта глава описывает все операторы, выражения и ключевые слова языка JavaScript. https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators

++ #инкремент

-- #декремент

a + b (operand1 operator operand2)

### Чистая функция

`#Чистая функция #Pure Function`

https://habr.com/ru/post/437512/
Функция должна удовлетворять двум условиям, чтобы считаться «чистой»:

- Каждый раз функция возвращает одинаковый результат, когда она вызывается с тем же набором аргументов
- Нет побочных эффектов

Логика происходит внутри без взаимодействия с глобальными переменными.
Такие функции можно переиспользовать.
Функция чистая, если не имеет побочных эффектов и каждый раз возвращает одинаковый результат, когда она вызывается с тем же набором аргументов.
Побочные эффекты включают: меняющийся вход, HTTP-вызовы, запись на диск, вывод на экран (если функция предназначениа для другого).
Вы можете безопасно клонировать, а затем менять входные параметры. Просто оставьте оригинал без изменений.
...spread — это самый простой способ клонирования объектов и массивов.

### freeze

`#freeze #запрет изменения объекта`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze
Метод Object.freeze() замораживает объект: это значит, что он предотвращает добавление новых свойств к объекту, удаление старых свойств из объекта и изменение существующих свойств или значения их атрибутов перечисляемости, настраиваемости и записываемости.
В сущности, объект становится эффективно неизменным. Метод возвращает замороженный объект.
Для вложенных объектов для предотвращения изменения необходимо так же вызывать метод freeze рекурсивно - глубокая заморозка.

### Дескрипторы

`#Дескрипторы`

https://behemothoz.gitbooks.io/js-learn/content/object/deskriptori-svoistv.html

https://learn.javascript.ru/descriptors-getters-setters

Дескриптор `свойства` – это обычный JavaScript-объект, описывающий атрибуты и значение свойства.

Дескрипторы свойств, присутствующие в объектах, бывают двух основных типов: дескрипторы данных и дескрипторы доступа.

Дескриптор `данных` - это свойство, имеющее значение, которое может быть (а может и не быть) записываемым.

Дескриптор `доступа` - это свойство, описываемое парой функций - геттером и сеттером.

Дескриптор может быть только чем-то одним из этих двух типов. Он не может быть одновременно обоими.

#### get, set

`#get #set #getter #setter #геттер #сеттер`

https://learn.javascript.ru/property-accessors

Свойство объекта задаётся как функция get prop(), при получении prop выполнится функция в теле prop(). При использовании this.prop в get и set, чтобы не зациклить используется другая переменная, как правило \_prop. В set prop(value) должно подаваться value. В итоге в объекте данные хранятся и берутся не из той к которой обращаемся из вне. Пример: es/es-6-8/8_classes.js https://github.com/SpawnMetal/es-6-8

### Reflect

`#Reflect #Рефлект`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Reflect

es/es-6-8/13_reflect.js https://github.com/SpawnMetal/es-6-8

patterns/2 structural/9_proxy.js https://github.com/SpawnMetal/es-6-8

Reflect - это встроенный объект, который предоставляет методы для перехватывания JavaScript операций. Эти методы аналогичны методам proxy handler ов. Reflect - это не функциональный, а простой объект, он не является сконструированным.

В отличие от большинства глобальных объектов, Reflect - это не конструктор. Вы не можете использовать его с оператором new или вызывать Reflect, как функцию. Все свойства и методы объекта Reflect являются статическими (так же, как и у объекта Math).

### Proxy

`#Proxy #Прокси`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Proxy

Объект Proxy позволяет создать прокси для другого объекта, может перехватывать и переопределить основные операции для данного объекта.

### ??

`#Nullable #??`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator

Оператор нулевого слияния (??) это логический оператор, который возвращает значение правого операнда когда значение левого операнда равно null или undefined, в противном случае будет возвращено значение левого операнда.

### ?.

`#Optional #?.`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Optional_chaining

Оператор опциональной последовательности ?. позволяет получить значение свойства, находящегося на любом уровне вложенности в цепочке связанных между собой объектов, без необходимости проверять каждое из промежуточных свойств в ней на существование. ?. работает подобно оператору ., за исключением того, что не выбрасывает исключение, если объект, к свойству или методу которого идёт обращение, равен null или undefined. В этих случаях он возвращает undefined.

Таким образом, мы получаем более короткий и понятный код при обращении к вложенным по цепочке свойствам объекта, когда есть вероятность, что какое-то из них отсутствует.

### Типы данных

`#Типы данных`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures

Пример приведения типов examples\examples.js https://github.com/SpawnMetal/examples

В js 8 типов данных: null, undefined, boolean, number, string, bigint, object, symbol, среди них все примитивные, кроме object

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/typeof

- typeof null === 'object' см #null
- typeof function () {} === 'function'
- typeof class C {} === 'function'
- typeof Infinity === 'number'
- typeof NaN === 'number'

Стоит отметить два особых случая работы оператора typeof: возврат "object" для значения null и "function" для функций: первое принято считать ошибкой языка, сохраненной ради обратной совместимости, второе является условностью, удобной для проверки на принадлежность значения категории функций, где функция - это особый, "вызываемый", объект.

Если проверить тип структуры всё же необходимо, то в этом случае желательно использовать оператор instanceof, так как именно он отвечает на вопрос о том, какой конструктор был использован для создания структуры.

Девять вопросов о работе с памятью в V8 https://habr.com/ru/company/ruvds/blog/350240/

#### Number

`#Number`

https://learn.javascript.ru/number

В соответствии со стандартом ECMAScript, существует только один числовой тип, который представляет собой 64-битное (8 байт) число двойной точности согласно стандарту `IEEE 754`

`52` из них используется для `хранения цифр`, `11` из них для `хранения положения десятичной точки` (если число целое, то хранится `0`), и `один бит отведён на хранение знака`

`Число двойной точности (Double precision, Double)` https://ru.wikipedia.org/wiki/Число_двойной_точности

`IEEE 754-2008` https://ru.wikipedia.org/wiki/IEEE_754-2008

Числа двойной точности с плавающей запятой эквивалентны по точности числу с `15-17 значащими десятичными цифрами` (в среднем `16,3`) в диапазоне примерно `от 10^-308 до 10^308`

Максимальное значение: `Number.MAX_SAFE_INTEGER`

alert( 0.1 + 0.2 ); // 0.30000000000000004. Решение: Number((0.1 + 0.2).`toFixed`(2)) // '0.30' = 0.3

Число хранится в памяти в бинарной форме, как последовательность бит – единиц и нулей. Но дроби, такие как 0.1, 0.2, которые выглядят довольно просто в десятичной системе счисления, на самом деле являются бесконечной дробью в двоичной форме.

Другими словами, что такое 0.1? Это единица делённая на десять — 1/10, одна десятая. В десятичной системе счисления такие числа легко представимы, по сравнению с одной третьей: 1/3, которая становится бесконечной дробью 0.33333(3).

Деление на 10 гарантированно хорошо работает в десятичной системе, но деление на 3 – нет. По той же причине и в двоичной системе счисления, деление на 2 обязательно сработает, а 1/10 становится бесконечной дробью.

В JavaScript нет возможности для хранения точных значений 0.1 или 0.2, используя двоичную систему, точно также, как нет возможности хранить одну третью в десятичной системе счисления.

Числовой формат `IEEE-754` решает эту проблему путём округления до ближайшего возможного числа. Правила округления обычно не позволяют нам увидеть эту «крошечную потерю точности», но она существует.

Пример:

```js
alert((0.1).toFixed(20)) // 0.10000000000000000555
```

И когда мы суммируем 2 числа, их «неточности» тоже суммируются.

Вот почему 0.1 + 0.2 – это не совсем 0.3.

Не только в JavaScript

Справедливости ради заметим, что ошибка в точности вычислений для чисел с плавающей точкой сохраняется в любом другом языке, где используется формат IEEE 754, включая PHP, Java, C, Perl, Ruby.

Можно ли обойти проблему? Конечно, наиболее надёжный способ — это округлить результат используя метод с математическим округлением toFixed(n):

```js
let sum = 0.1 + 0.2
alert(sum.toFixed(2)) // 0.30
```

Помните, что метод toFixed всегда возвращает строку. Это гарантирует, что результат будет с заданным количеством цифр в десятичной части. Также это удобно для форматирования цен в интернет-магазине $0.30. В других случаях можно использовать унарный оператор +, чтобы преобразовать строку в число:

```js
let sum = 0.1 + 0.2
alert(+sum.toFixed(2)) // 0.3
```

#### BigInt

`#BigInt`

Является встроенным объектом, который предоставляет способ представления целых чисел, которые `больше 2^53`, что является наибольшим числом, которое JavaScript может надёжно представить с помощью Number примитива.

Например `19241924124n`

#### String

`#String`

Он представляет собой цепочку «элементов» 16-битных беззнаковых целочисленных значений. Каждый такой элемент занимает свою позицию в строке. Первый элемент имеет индекс 0, следующий — 1, и так далее. Длина строки — это количество элементов в ней.

#### null

`#null`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/null

Значение `null` представляет `отсутствие` какого-либо объектного `значения`. В JavaScript, `null является примитивом`, и в контексте логических операций, рассматривается как ложное (falsy).

Занимает в памяти несколько байтов. Точный объем используемой памяти будет зависеть от реализации среды выполнения JavaScript, но обычно считается незначительным по сравнению с другими типами данных.

https://developer.mozilla.org/ru/docs/Glossary/Null

В **информатике**, значение `null` представляет `ссылку`, которая указывает, обычно намеренно, на несуществующий или некорректный объект или адрес. Смысл null-ссылки различается от языка к языку.

В JavaScript, `null` – это значение, специально обозначенное как примитив, так как по поведению это в самом деле видимый примитив. Но при этом `от null унаследованы все остальные Объекты`, поэтому, несмотря на то, что `null` возвращает примитивное значение, его тип это `объект`: `typeof null === 'object'`

**Поэтому то, что typeof null === 'object' является некой не точностью, которую оставили намеренно, а null - это примитив и имеет тип null https://youtu.be/M_pclb-58ZY?t=464**

#### Object

`#Object #Объект #Массив #Array`

`Object` Object.prototype.toString.call(obj) === '[object Object]' https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object

`Array` Object.prototype.toString.call(arr) === '[object Array]' https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array

Объект JavaScript — это таблица соотношений между ключами и значениями. `Ключи` — это `строки` (или `Symbol` задаётся с помощью динамического ключа), а `значения могут быть любыми`. Это делает объекты полностью отвечающими определению `хеш-таблицы` https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures

Хеш-таблица — это структура данных, реализующая интерфейс ассоциативного массива, а именно, она позволяет хранить пары (ключ, значение) и выполнять три операции: операцию добавления новой пары, операцию поиска и операцию удаления пары по ключу. https://ru.wikipedia.org/wiki/Хеш-таблица

Есть `два типа свойств`: `свойство-значение` и `свойство-акцессор` (свойство, обёрнутое в `геттер` и `сеттер`). Они отличаются определёнными атрибутами. См [Дескрипторы](#Дескрипторы)

Функции — это обычные объекты, имеющие дополнительную возможность быть вызванными для исполнения.

JavaScript имеет стандартную библиотеку встроенных объектов https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects

Object.`getOwnPropertyDescriptor`(obj, prop) позволяет получить параметры свойства: `configurable`, `enumerable`, `value`, `writable` https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptor

`#Список #Односвязанный #Двусвязанный`

[Связанные списки в JavaScript][linked-list]

##### Object

[Клонирование объектов](#Клонирование-объектов)

Переменная содержит `ссылку`, а не само значение.

Переприсвоенная ссылка аргументу функции не повлияет на исходный объект.

Параметры всегда передаются по значению, но в переменные, представляющие объекты, записаны ссылки на объекты. Поэтому, когда в функцию передают объект и меняют свойство этого объекта, это изменение сохраняется в объекте и при выходе из функции. В результате возникает ощущение того, что параметры в функции передаются по ссылке. Но если изменить значение переменной, представляющей объект, это изменение не повлияет на объекты, находящиеся за пределами функции.

Вот пример:

```js
function changeStuff(a, b, c) {
  a = a * 10
  b.item = 'changed'
  c = {item: 'changed'}
}

var num = 10
var obj1 = {item: 'unchanged'}
var obj2 = {item: 'unchanged'}

changeStuff(num, obj1, obj2)

console.log(num) // 10
console.log(obj1.item) // changed
console.log(obj2.item) // unchanged
```

###### Слабые ссылки

`#Слабые #Ссылки`

https://habr.com/ru/post/163679

Слабые ссылки отличаются от обычных тем, что не препятствуют удалению объекта из памяти. Когда память, занимаемая объектом, освобождается, все указывающие на него слабые ссылки обнуляются. В некоторых реализациях в этом случае также вызывается установленный пользователем обработчик — финализатор.

Например отображение, в котором ключом будет объект, а значением — вспомогательная информация.

Пример функций `#WeakMap #WeakSet`

##### Symbol

`#Символы #Symbol`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Symbol

Создаёт уникальное значение, всегда, не видим для перебора через in

Символ (анг. Symbol) — это уникальный и неизменяемый тип данных, который может быть использован как идентификатор для свойств объектов. Символьный объект (анг. symbol object) — это объект-обёртка (англ. wrapper) для примитивного символьного типа.

##### Map, Set, WeakMap, WeakSet

`#Коллекции #Map #Set #WeakMap #WeakSet`

https://learn.javascript.ru/map-set

`Map` – это коллекция ключ/значение, как и Object. Но основное отличие в том, что Map позволяет использовать ключи любого типа.

`Map` - реализация простого ассоциативного массива (словаря). Он содержит данные в виде набора пар ключ/значение(ключи уникальны) и предоставляет методы для доступа и манипулирования этими данными. Ключом может быть любой тип.

Объект `Set` – это особый вид коллекции: «множество» значений (без ключей), где каждое значение может появляться только один раз.

`Разница` между `Map` и `WeakMap`:

1. Только у Map ключи являются перечисляемыми. Это позволяет оптимизировать сборку мусора для WeakMap.
2. #Слабые ссылки у WeakMap WeakSet - сборщик мусора очистит ссылки на несуществующие объекты (в ключе)
3. Map позволяет использовать ключи любого типа, WeakMap - ключи только объекты

`WeakMap` https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/WeakMap

Объект `WeakSet` - коллекция, элементами которой могут быть только объекты. Ссылки на эти объекты в WeakSet являются слабыми. Каждый объект может быть добавлен в WeakSet только один раз.

`WeakSet` https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/WeakSet

##### Иммутабельность

`#Иммутабельность`

Все типы данных в JavaScript, кроме объектов, являются иммутабельными (значения не могут быть модифицированы, а только перезаписаны новым полным значением). Например, в отличии от C, где строку можно посимвольно корректировать, в JavaScript строки пересоздаются только полностью. Значения таких типов называются «примитивными значениями».

### new

`#new`

Оператор (операторная функция) new создаёт экземпляр объекта, встроенного или определённого пользователем, имеющего конструктор. https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/new

Не применим к стрелочным функциям

#### Instance

`#Instance #экземпляр #инстанс`

```js
const cat = new Cat()
```

cat - Экземпляр (instance) класса

Статические методы и свойства вызываются без инстанцирования их класса, и не могут быть вызваны у экземпляров (instance) класса.

#### new Function

`#Function`

https://learn.javascript.ru/new-function

Функции, объявленные через new Function, имеют `Environment`, ссылающийся на глобальное лексическое окружение, а не на родительское. Поэтому они не могут использовать внешние локальные переменные. Но это очень хорошо, потому что страхует нас от ошибок. Переданные явно параметры – гораздо лучшее архитектурное решение, которое не вызывает проблем у минификаторов. См [Scope](#Scope)

```js
new Function('a', 'b', 'return a + b') // стандартный синтаксис
new Function('a,b', 'return a + b') // через запятую в одной строке
new Function('a , b', 'return a + b') // через запятую с пробелами в одной строке
```

### delete

`#delete`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/delete

Оператор delete удаляет свойство из объекта.

Не воздействует на простые переменные.

### reduce

`#reduce`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce

Метод reduce() применяет функцию reducer к каждому элементу массива (слева-направо), возвращая одно результирующее значение.

### for

`#for`

#### of

`#of #Перебор #Итерируемость #Итерируемый #Iterator #Iteration`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/for...of

Оператор `for...of` выполняет цикл обхода `итерируемых объектов` (включая `Array`, `Map`, `Set`, `объект аргументов` и `подобных`), вызывая на каждом шаге итерации операторы для каждого значения из различных свойств объекта.

Наличие `Symbol.iterator` определяет итерируемость

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Iteration_protocols

#### in

`#in #Перечисление`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Statements/for...in

Цикл `for...in` проходит через перечисляемые свойства объекта. Он пройдёт по каждому отдельному элементу.

https://developer.mozilla.org/ru/docs/Web/JavaScript/Enumerability_and_ownership_of_properties

Свойства, определённые через `Object.defineProperty` получают по умолчанию значение флага `Enumerable` равным `false`

Свойство `Symbol не перечисляется`

### Регулярные выражения

`#Регулярные выражения #Regular`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Regular_Expressions

https://learn.javascript.ru/regular-expressions

Регулярные выражения - это шаблоны, используемые для сопоставления последовательностей символов в строках. В JavaScript регулярные выражения также являются объектами. Эти шаблоны используются в методах `exec` и `test` объекта `RegExp`, а также `match`, `replace`, `search` и `split` объекта `String`.

Пример localhost\examples\regular.js https://github.com/SpawnMetal/examples

```js
regexp = new RegExp('шаблон', 'флаги')
regexp = /шаблон/gim // с флагами gmi
```

## W3C DOM Events

`#W3C #DOM #Events`

https://learn.javascript.ru/dom-nodes

https://developer.mozilla.org/ru/docs/Web/API/Document_Object_Model

`DOM` - дерево

Основой HTML-документа являются теги.

В соответствии с объектной моделью документа («Document Object Model», коротко DOM), каждый HTML-тег является объектом.

Организация, разрабатывающая и внедряющая технологические стандарты для Всемирной паутины. https://ru.wikipedia.org/wiki/Консорциум_Всемирной_паутины

W3C, DOM Events, UI Events https://www.w3.org/TR/DOM-Level-3-Events/

`#let #const #var #Необъявленная переменная #Переменные #Объявление`

let и const существуют в scope, не всплывают, const не переприсваивается

var всплывает в начало функции

Необъявленная переменная создаётся при присвоении необъявленному идентификатору значения, всплывает до глобальной области либо выдаст ошибку в strict

Объявленные переменные с не присвоенным значением = undefined

null == undefined в !strict

### Всплытие у переменных

`#Всплытие #Поднятие #Погружение #Перехват #Hoisting`

https://developer.mozilla.org/ru/docs/Glossary/Hoisting

У var и function

Function Expression, стрелочные функции, class не всплывают

`#Временная #мёртвая #зона» (#Temporal #Dead #Zone, #TDZ)`

В коде имеется зона, простирающаяся от входа в область видимости до объявления переменной или константы. При обращении к переменной или константе в этой зоне будет выдана ошибка. Это и есть «временная мёртвая зона» (Temporal Dead Zone, TDZ).

https://learn.javascript.ru/var

`hoisting`: это то, где объявлена переменная, какое у неё значение при обращении, когда его можно менять, где эта переменная доступна.

Так же поведение например var называется «hoisting» (всплытие, поднятие), потому что все объявления переменных var «всплывают» в самый верх функции.

Объявления переменных (declaration, декларация) «всплывают», но присваивания значений (initialization, инициализация) – нет (переменные имеют значение undefined до строки с присвоением значения).

### Всплытие у events

`#Всплытие #Поднятие #Погружение #Перехват #Hoisting`

https://learn.javascript.ru/bubbling-and-capturing

`event.preventDefault()` - Метод preventDefault() интерфейса Event сообщает User agent, что если событие не обрабатывается явно, его действие по умолчанию не должно выполняться так, как обычно. Событие продолжает распространяться как обычно, до тех пор, пока один из его обработчиков не вызывает методы `stopPropagation()` или `stopImmediatePropagation()`, любой из которых сразу же прекращает распространение. Как отмечено ниже, вызов метода `preventDefault()` для события, не подлежащего отмене, например события, отправленного через `EventTarget.dispatchEvent()`, без указания cancelable: true не имеет эффекта. https://developer.mozilla.org/ru/docs/Web/API/Event/preventDefault

Когда на элементе происходит событие, обработчики сначала срабатывают на нём, потом на его родителе, затем выше и так далее, вверх по цепочке предков.

Почти все события всплывают. Например, событие focus не всплывает.

Но любой промежуточный обработчик может решить, что событие полностью обработано, и остановить всплытие. Для этого нужно вызвать метод `event.stopPropagation()`. Он препятствует продвижению события дальше, но на текущем элементе все обработчики будут вызваны.

Для того, чтобы полностью остановить обработку, существует метод `event.stopImmediatePropagation()`. Он не только предотвращает всплытие, но и останавливает обработку событий на текущем элементе.

Существует ещё одна фаза из жизненного цикла события – «погружение» (иногда её называют «перехват»). Она очень редко используется в реальном коде, однако тоже может быть полезной. Отлавливается с помощью addEventListener с {capture: true}

При наступлении события – самый глубоко вложенный элемент, на котором оно произошло, помечается как «целевой» (event.target).

Затем событие сначала двигается вниз от корня документа к event.target, по пути вызывая обработчики, поставленные через addEventListener(...., true), где true – это сокращение для {capture: true}.

Далее обработчики вызываются на целевом элементе.

Далее событие двигается от event.target вверх к корню документа, по пути вызывая обработчики, поставленные через on<event> и addEventListener без третьего аргумента или с третьим аргументом равным false.

Каждый обработчик имеет доступ к свойствам события event:

- `event.target`: самый глубокий элемент, на котором произошло событие.
- `event.currentTarget (=this)`: элемент, на котором в данный момент сработал обработчик (тот, на котором «висит» конкретный обработчик)
- `event.eventPhase`: на какой фазе он сработал (погружение=1, фаза цели=2, всплытие=3).
- `Фаза погружения (capturing phase)`: событие сначала идёт сверху вниз (от target к родителям).
- `Фаза цели (target phase)`: событие достигло целевого(исходного) элемента.
- `Фаза всплытия (bubbling stage)`: событие начинает всплывать (от родителей к target).

Всплытие и погружение являются основой для «#делегирования событий» – очень мощного приёма обработки событий.

### Динамический ключ

`#Динамический ключ`

Динамический ключ - name: value, ключом будет name, но если его обернуть в [], то у ключа [name], name будет переменной

### Деструктуризация

`#Деструктуризация`

https://learn.javascript.ru/destructuring

Деструктуризация (destructuring assignment) – это особый синтаксис присваивания, при котором можно присвоить массив или объект сразу нескольким переменным, разбив его на части.

```js
const fio = {firstName: 'name', lastName: 'family'}
spreadFIO(fio)
function spreadFIO({firstName, lastName}) {
  alert(firstName) // name
  alert(lastName) // family
}
```

```js
// ...spread
{...fio}
[...fio]
```

```js
// Переприсвоение
fio = {...fio, firstName: 'test'}
alert(firstName) // test
alert(lastName) // family
```

```js
let [firstName, lastName] = ['Илья', 'Кантор']

alert(firstName) // Илья
alert(lastName) // Кантор
```

```js
let options = {
  title: 'Меню',
  width: 100,
  height: 200,
}

let {title, width, height} = options

alert(title) // Меню
alert(width) // 100
alert(height) // 200

let {title: t, width: w, height: h} = options

alert(t) // Меню
alert(w) // 100
alert(h) // 200
```

#### spread, rest

`#spread #rest`
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Spread_syntax

Spread syntax позволяет расширить доступные для итерации элементы (например, массивы или строки) в местах

- для функций: где ожидаемое количество аргументов для вызовов функций равно нулю или больше нуля
- для элементов (литералов массива)
- для выражений объектов: в местах, где количество пар "ключ-значение" должно быть равно нулю или больше (для объектных литералов)

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions/Rest_parameters

Синтаксис параметра rest позволяет функции принимать неопределенное число аргументов в виде массива, обеспечивая способ представления вариадических функций в JavaScript.

rest - это Array

В ES5 использовался arguments[i], но это не Array https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Functions/arguments

#### Клонирование объектов

`#Копирование #Клонирование объектов и ссылки`

https://learn.javascript.ru/object-copy

Объекты хранят ссылку в памяти на значение, а не само значение.

Для глубокого копирования необходимо использовать функцию `const clone = structuredClone(original, options?)` https://developer.mozilla.org/en-US/docs/Web/API/structuredClone

Алгоритм структурированного клонирования https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Structured_clone_algorithm

Для «простого клонирования» объекта можно использовать `{...spread}` либо `Object.assign` - работает аналогично. Необходимо помнить, что данные методы не делают глубокое клонирование объекта. Если внутри копируемого объекта есть свойство, значение которого не является примитивом, оно будет передано по ссылке. Для создания !== клона объекта можно воспользоваться методом из сторонней JavaScript-библиотеки `lodash` - `_.cloneDeep(obj)`, но рекурсивная вложенность не поддерживается, а так же сложные типы, как например дата, будут преобразованы в строку, таких изъян нет у `structuredClone`, поэтому лучше пользоваться именно `structuredClone`.

Встроенным в JS способом можно скопировать использовав `JSON.stringify` и `JSON.parse`.

### Тернарный оператор

`#Тернарный оператор`

Операнд(условие) ? операнд(условие выполнено) : операнд(else)

## Technology

### React

https://reactjs.org

https://developer.mozilla.org/ru/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started

React (иногда React.js или ReactJS) — JavaScript-библиотека с открытым исходным кодом для разработки пользовательских интерфейсов. Разработчики Facebook.

В качестве библиотеки для разработки пользовательских интерфейсов React часто используется с другими библиотеками, такими как Redux либо Mobx.

Топ-10 библиотек для React на GitHub https://habr.com/ru/company/ruvds/blog/345060/

Material UI, React-Bootstrap, Ant-Design, StoryBook, Gatsby, Enzyme, Blueprint, Spectacle, Elemental UI, Grommet, Mozaik

Пример GitHub https://github.com/SpawnMetal/test_with_questions

Пример локально localhost\test_with_questions

https://ru.reactjs.org/docs/create-a-new-react-app.html

https://create-react-app.dev

Create React App сразу всё ставит.

Create React App — удобная среда для изучения React и лучший способ начать создание нового одностраничного приложения на React.

Инструмент настраивает среду для использования новейших возможностей JavaScript, оптимизирует приложение для продакшена и обеспечивает комфорт во время разработки. Вам понадобятся Node.js не ниже версии 8.10 и npm не ниже версии 5.6 на вашем компьютере. Для создания проекта выполните команды:

- `npm install react-scripts@latest`: обновление инструментов
- `npm i react-router-dom`: для роутинга в react

React позволяет использовать synthetic events - обёртка эвентов для кроссбраузерности, накручивает свои механизмы.

Презентационный компоненты выводит данные и работает с props, а контейнер компонент формирует их для презентационного и работает с state.

В render нельзя менять состояние, иначе приложение уйдёт в рекурсию.

Если отнаследоваться от Pure Component, то React автоматически реализует shouldComponentUpdate, оптимизируя работу приложения.

Для оптимизации приложения используются shouldComponentUpdate, Pure component, React.memo() - для функциональных компонентов.

Для отрисовки компонентов используются функциональные компоненты, они более быстрые, но если нужны доступы до жизненных этапов в более сложном компоненте, тогда нужно использовать классовый компонент.

Хуки позволяют в функциональных компонентах взаимодействовать с жизненными этапами и механизмами React.
prop drilling - множественная передача пропсов, используется контекст, чтобы это избежать либо MobX.

Для валидации пропсов используется библиотека prop-types - динамическая типизация. Flow - для статической, аналог - Typescript

eject нужен, чтобы получить доступ к конфигурации приложения, если оно уже было настроено с помощью WebPack и настроить его отдельно.

PUBLIC_URL ведёт в папку public, Например <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />

Если вы ищете полноценное решение, которое может валидировать ввод, запомнить посещённые поля формы и обработать её отправку, присмотритесь к Formik. Эта библиотека построена на принципах управляемых компонентов и управления состоянием, так что не пренебрегайте их изучением. https://ru.reactjs.org/docs/forms.html https://jaredpalmer.com/formik

- `npx create-react-app my-app`: установит тесты, git, webpack, babel и др

Примеры:

localhost\my-app пример create-react-app

localhost\react https://github.com/SpawnMetal/react

localhost\react2 https://github.com/SpawnMetal/react2 https://youtu.be/xJZa2_aldDs

#### Жизненный цикл

https://disk.yandex.ru/i/4N5roTR26xwcsw

```txt
Mounting                              Updating                             Unmounting
    |                                     |                                   |
constructor               New props / setState() / forceUpdate()              |
            \           /                                                     |
                render                                                        |
      React updates DOM and refs                                              |
    /                            \                                            |
componentDidMount                 componentDidUpdate                 componentWillUnmount
```

```jsx
export const Child = ({num}) => {
  console.log('child: render')

  useLayoutEffect(() => {
    console.log('child: layout effect')

    return () => {
      console.log('child: cleanup layout effect')
    }
  }, [num])

  useEffect(() => {
    console.log('child: effect')
    return () => {
      console.log('child: cleanup effect')
    }
  }, [num])

  return null
}

export const App = () => {
  const [num, setNum] = useState(0)

  console.log('parent: render')

  function clickHandler() {
    setNum(prev => prev + 1)
  }

  useLayoutEffect(() => {
    console.log('parent: layout effect')

    return () => {
      console.log('parent: cleanup layout effect')
    }
  }, [num])

  useEffect(() => {
    console.log('parent: effect')
    return () => {
      console.log('parent: cleanup effect')
    }
  }, [num])

  return (
    <>
      <Child num={num} />
      <button onClick={clickHandler}>render</button>
      <div style={{fontSize: '45px', textAlign: 'center'}}>{num}</div>
    </>
  )
}

// При рендере:
// parent: render
// develop // parent: render
// child: render
// develop // child: render
// child: layout effect
// parent: layout effect
// child: effect
// parent: effect
// child: cleanup layout effect
// parent: cleanup layout effect
// child: cleanup effect
// parent: cleanup effect
// child: layout effect
// parent: layout effect
// child: effect
// parent: effect

// После нажатия на кнопку:
// parent: render
// develop // parent: render
// child: render
// develop // child: render
// child: cleanup layout effect
// parent: cleanup layout effect
// child: layout effect
// parent: layout effect
// child: cleanup effect
// parent: cleanup effect
// child: effect
// parent: effect
```

#### Хук

`#Хук #Hook`

https://ru.reactjs.org/docs/hooks-intro.html

https://ru.reactjs.org/docs/hooks-reference.html

https://youtu.be/9KJxaFHotqI

`Хуки` — нововведение в React 16.8, которое позволяет использовать состояние и другие возможности React без написания классов.

По конвенции при создании своего хука функция должна начинаться с use

Хорошей практикой считается описание входящих свойств в нужный компонент, чтобы избегать потенциальных ошибок с передачей типов значений

Для этого раньше использовался `npm i prop-types`

##### useState

`#useState`

https://ru.reactjs.org/docs/hooks-reference.html#usestate

https://youtu.be/9KJxaFHotqI?t=71

Пример в localhost\react2 https://github.com/SpawnMetal/react2

```jsx
const [state, setState] = useState(initialState)
```

Возвращает текущее значение в первом параметре деструктуризации и задаёт с помощью хука (второй параметр) начальное состояние значений.

Если в setState передаётся callback, то мы будем иметь доступ к предыдущенму значению:

```jsx
setState(prev => prev + 1)
```

Функция возвращает всегда два значения в массиве, первое - это дефолтное состояние, заданное сейчас, а второй элемент - коллбэк, с помощью него можно менять значения

После вызова setState, значение state останется прежним и обновится только после рендера

Если в useState передаётся callback, то произойдёт ленивая инициализация состояния, можно использовать при дорогостоящих вычислениях https://ru.legacy.reactjs.org/docs/hooks-reference.html#lazy-initial-state

```jsx
// Ленивая инициализация состояния
const [state, setState] = useState(() => {
  const initialState = someExpensiveComputation(props)
  return initialState
})
```

##### useEffect

`#useEffect`

https://ru.reactjs.org/docs/hooks-reference.html#useeffect

https://youtu.be/9KJxaFHotqI?t=1400

Запускается после каждого завершённого рендера: разметки (Layout) и отрисовки (Paint).

Передаётся два параметра, в первом коллбэк, во втором массив со списком зависимостей, чтобы отрабатывал коллбэк, переданный в первый параметр

Он выполняет ту же роль, что и componentDidMount, componentDidUpdate и componentWillUnmount в React-классах, объединив их в единый API.

StrictMode выполняет рендеринг компонентов дважды в `development` режиме, но не в `production`. По мнению разработчиков React - это позволяет обнаружить некоторые проблемы в вашем коде, если таковые будут и предупредить Вас об этом. https://ru.reactjs.org/docs/strict-mode.html#detecting-unexpected-side-effects

При асинхронном получении данных не отображает для SEO

1. `Каждый раз (componentDidMount + componentDidUpdate)`: Не передавать второй параметр. https://ru.legacy.reactjs.org/docs/hooks-reference.html#timing-of-effects

```jsx
useEffect(() => {})
```

2. ```Один раз (componentDidMount)`: Передаётся пустой массив вторым параметром. https://ru.legacy.reactjs.org/docs/hooks-reference.html#conditionally-firing-an-effect

```jsx
useEffect(() => {}, [])
```

3. `Условное срабатывание эффекта` https://ru.legacy.reactjs.org/docs/hooks-reference.html#conditionally-firing-an-effect

```jsx
useEffect(() => {}, [state1, state2, ..., stateN])
```

4. `Очистка эффекта (componentWillUnmount)`: Вернуть функцию. https://ru.legacy.reactjs.org/docs/hooks-reference.html#cleaning-up-an-effect

```jsx
useEffect(() => {
  return () => {}
}, [могут быть зависимости или полностью отсутствовать второй параметр])
```

##### useLayoutEffect

`#useLayoutEffect`

https://ru.legacy.reactjs.org/docs/hooks-reference.html#timing-of-effects

https://codesandbox.io/p/sandbox/uselayouteffect-dg3ph5

Необходим для вызова перед компоновкой (Layout), чтобы не выводить то, что будет снова перерисовано, а сразу скомпоновать как нужно. Происходит перед useEffect

##### useContext

`#useContext`

https://ru.reactjs.org/docs/hooks-reference.html#usecontext

Может быть удобно, чтобы не тянуть всё через пропсы.

##### useCallback

`#useCallback`

https://ru.legacy.reactjs.org/docs/hooks-reference.html#usecallback

https://www.youtube.com/watch?v=9KJxaFHotqI&t=3579s

```jsx
const memoizedCallback = useCallback(() => {
  doSomething(a, b)
}, [a, b])
```

Позволяет реализовать зависимость, при которой будет вызываться функция, наподобие второго аргумента в useEffect.

При setState происходит рендер компонента и при переданном useEffect callback'е он будет срабатывать из-за пересоздания функций в компоненте.

Таким образом будет вызываться callback лишний раз при вызове одного из setState в компоненте.

Чтобы этого избежать, мы оборачиваем callback в useCallback, тем самым как бы кэшируем функцию и при рендере компонента callback лишний раз вызываться не будет.

##### useMemo

`#useMemo`

https://ru.legacy.reactjs.org/docs/hooks-reference.html#usememo

https://youtu.be/9KJxaFHotqI?t=2887

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b])
```

Возвращает мемоизированное значение.

Если массив не был передан, новое значение будет вычисляться при каждом рендере.

useMemo, запускается во время рендеринга - до useEffect.

Вы можете использовать useMemo как оптимизацию производительности, а не как семантическую гарантию. В будущем React может решить «забыть» некоторые ранее мемоизированные значения и пересчитать их при следующем рендере, например, чтобы освободить память для компонентов вне области видимости экрана. Напишите свой код, чтобы он по-прежнему работал без useMemo, а затем добавьте его для оптимизации производительности.

##### useRef

`#useRef`

https://ru.legacy.reactjs.org/docs/hooks-reference.html#useref

https://youtu.be/Zn54xUCkh9s?si=_bxz7JRF4lNp4Lbh

1. Используется для сохранения переменной, которая не будет вызывать рендер https://codesandbox.io/p/sandbox/useref-previous-r2524w
2. Используется для создания ссылки на элемент https://codesandbox.io/p/sandbox/useref-element-5nk2kp

#### memo

`#memo`

https://react.dev/reference/react/memo

Git https://github.com/SpawnMetal/react-memo

React.memo позволяет пропустить повторный рендеринг компонента, если его свойства не изменились.

React обычно перерисовывает компонент каждый раз, когда перерисовывает его родительский элемент. С помощью memo вы можете создать компонент, который React не будет повторно отображать при повторной визуализации его родителя, если его новые свойства такие же, как и старые. Такой компонент называется мемоизированным .

Чтобы запомнить компонент, оберните его memo и используйте возвращаемое значение вместо исходного компонента:

```jsx
const Greeting = memo(function Greeting({name}) {
  return <h1>Hello, {name}!</h1>
})

export default Greeting
```

#### JSX

https://ru.reactjs.org/docs/introducing-jsx.html

https://facebook.github.io/jsx

`JavaScript XML (JSX)` — это расширение синтаксиса JavaScript, которое позволяет использовать похожий на HTML синтаксис для описания структуры интерфейса. Как правило, компоненты написаны с использованием JSX, но также есть возможность использования обычного JavaScript.

JSX напоминает другой язык, созданный в компании Фейсбук для расширения PHP, XHP.

#### Throttle и Debounce

`#Throttle #Debounce`

https://dev.to/andreysm/ispolzuiem-throttle-i-debounce-v-react-3cn9

Throttle и Debounce решают задачи оптимизации.

Throttle - пропускает вызовы функции с определённой периодичностью.

Debounce - откладывает вызов функции до того момента, когда с последнего вызова пройдёт определённое количество времени.

Например с использованием метода Throttle событие будет срабатывать каждые n секунд, а с Debounce будет откладываться. Вместе получится, что событие может происходить не каждые 1 секунду, а через 5, когда пользователь прекратит действие и можно будет провести конечное вычисление.

#### React DevTools

`#ReactDeveloperTools #DevTools`

https://github.com/facebook/react/tree/master/packages/react-devtools

React DevTools доступен как встроенное расширение для браузеров Chrome и Firefox. Этот пакет позволяет вам отлаживать приложение React в другом месте (например, в мобильном браузере, встроенном веб-просмотре, Safari внутри iframe).

Он работает как с React DOM, так и с React Native.

#### React Native

https://facebook.github.io/react-native

Вы можете использовать React Native сегодня в своих существующих проектах для Android и iOS, или вы можете создать совершенно новое приложение с нуля.

#### React Router

`#Router`

- `npm install --save react-router-dom`: DOM bindings for React Router. https://www.npmjs.com/package/react-router-dom

https://reactrouter.com/en/main

React Router - популярная и полная библиотека маршрутизации для React.js, которая синхронизирует пользовательский интерфейс с URL-адресом. Он поддерживает ленивую загрузку кода, динамическое сопоставление маршрутов и обработку перехода по местоположению и первоначально был вдохновлен маршрутизатором Ember.

BrowserRouter https://reactrouter.com/en/main/router-components/browser-router

Router https://reactrouter.com/en/main/route/route#route

Link https://reactrouter.com/en/main/components/link

/ нужен иначе будет в консоль выводить No routes matched location "/"

Использовать Link роутера (не Mui), так же navigate. Например не вызовет useEffect и рендер при переходе обратно из /example например в /

```tsx
// App.tsx
import {BrowserRouter, Routes, Route} from 'react-router-dom'
import {Example} from './Example'

function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/example" element={<Example />} />
      </Routes>
    </BrowserRouter>
  )
}
```

```tsx
// Example.tsx
import React from 'react'
import {Link, useNavigate} from 'react-router-dom'

export function Example() {
  const navigate = useNavigate()
  return (
    <>
      <Link to="/">Home</Link>
      <p onClick={() => navigate(`/`)}>Home</p>
    </>
  )
}
```

#### shouldComponentUpdate

`#shouldComponentUpdate`

Используется для отмены рендера, если его делать не нужно, а состояние поменялось

#### componentDidMount

`#componentDidMount`

Срабатывает, когда компонент готов для работы. После этого можно использовать асинхрон.

#### React Fragment

`#ReactFragment #Fragment`

Используется, чтобы положить несколько элементов в один конейнер, например div, но сам div отображаться не будет, оптимизируя тем самым структуру dom

```html
<React.Fragment> Элементы </React.Fragment>
```

Так же можно использовать структуру `<></>`

### Babel

`#Babel`

https://babeljs.io

https://babeljs.io/setup#installation

Babel - это компилятор JavaScript

Babel - Бабель является свободным и открытым исходным кодом JavaScript transcompiler, который в основном используется для преобразования ECMAScript 2015+ кода (ES6 +) в обратной совместимости версию JavaScript, который может быть запущен на более старых двигателях JavaScript . Babel - это популярный инструмент для использования новейших функций языка программирования JavaScript.

### Material Design

`#Material Design`

Material Design (рус. Материальный дизайн) — стиль графического дизайна интерфейсов программного обеспечения и приложений, разработанный компанией Google.

#### Material UI

`#Material UI`

https://material-ui.com/ru

Material UI — это библиотека, которая позволяет создавать приложения в стиле Google Material Design с использованием компонентов React. Она упрощает веб-разработку, создание привлекательных пользовательских интерфейсов и одностраничных приложений.

Подбор цвета: https://material.io/resources/color

styled. Все компоненты MUI стилизованы с помощью этой styled() утилиты. https://mui.com/system/styled/

#### Materialize

`#Materialize`

https://materializecss.com/

Интерфейсный фреймворк Material Design

#### Material Design Lite

`#Material Design Lite`

https://getmdl.io/

От Google офф, шаблон для остальных, содержит только основы

#### Bootstrap Material Theme

`#Bootstrap Material Theme`

https://fezvrasta.github.io/bootstrap-material-design/

Как следует из названия, это не отдельный фреймворк, а просто тема для Bootstrap.

По сколько это тема для Bootstrap'a, то здесь есть все фишки из Bootstrap'a и все элементы из Material Design, есть даже встроенные значки в стиле Material.

### Axios

`#Axios`

https://axios-http.com

https://github.com/axios/axios

Axios - библиотека javascript, реализующая XMLHttpRequest в браузере и поддерживающая Promise API.

Axios — это широко известная JavaScript-библиотека. Она представляет собой HTTP-клиент, основанный на промисах и предназначенный для браузеров и для Node.js.

Конфигурация запроса (Request Config) https://axios-http.com/docs/req_config

Ответ (Response Schema) https://axios-http.com/docs/res_schema

Перехватчики (Interceptors) request и response https://axios-http.com/docs/interceptors

Методы https://axios-http.com/docs/api_intro

Прерывание (Cancellation) https://axios-http.com/docs/cancellation

### Lodash

`#Lodash`

https://lodash.com/

Для решения типовых задач, используется библиотека lodash

Lodash - библиотека JavaScript, которая предоставляет вспомогательные функции для общих задач разработки с использованием парадигмы функционального программирования.

### Webpack

`#Webpack`

https://webpack.js.org

Webpack - это пакет модулей JavaScript с открытым исходным кодом. Это пакет модулей в основном для JavaScript, но он может преобразовывать внешние ресурсы, такие как HTML, CSS и изображения, если включены соответствующие загрузчики. [7] webpack принимает модули с зависимостями и генерирует статические ресурсы, представляющие эти модули. [8]
Webpack берет зависимости и генерирует граф зависимостей, https://webpack.js.org/concepts/dependency-graph/
позволяющий веб-разработчикам использовать модульный подход для целей разработки своих веб-приложений. Его можно использовать из командной строки или настроить с помощью файла конфигурации с именем webpack.config.js . Этот файл используется для определения правил, плагинов и т. Д. Для проекта. (Веб-пакет легко расширяется с помощью правил, которые позволяют разработчикам писать собственные задачи, которые они хотят выполнять при объединении файлов.)

Запаковывает фалы проекта в один общий файл - bundle.js

Концепции https://webpack.js.org/concepts

`#Bundle #Бандл`: Единый файл, в который транспилирован код

### esbuild

`#esbuild`

https://esbuild.github.io/

https://runebook.dev/ru/docs/esbuild/api/index

Простой в использовании современный сборщик. Быстрее остальных намного.

Основные особенности:

- Экстремальная скорость без необходимости кэша
- Встроенный JavaScript , CSS , TypeScript и JSX.
- Простой API для CLI, JS и Go.
- Объединяет модули ESM и CommonJS.
- Объединяет CSS, включая модули CSS.
- Встряхивание деревьев, минимизация и исходные карты
- Локальный сервер , режим просмотра и плагины

### JScript

`#JScript`

JScript — сценарный язык программирования компании Microsoft, являющийся реализацией стандарта ECMAScript. Синтаксис JScript во многом аналогичен языку JavaScript. Язык JScript получил дальнейшее развитие в виде языка JScript.NET, который ориентирован на работу в рамках платформы Microsoft .NET. Несмотря на сходный синтаксис, это принципиально другой язык. Он более строго типизирован и компилируется, а не интерпретируется.

### CoffeeScript

`#CoffeeScript`

CoffeeScript - добавляет «синтаксический сахар» для JavaScript. Он вводит более короткий синтаксис, который позволяет писать чистый и лаконичный код. Обычно такое нравится Ruby-программистам.

### Flow

`#Flow #Типизация`

Flow - тоже добавляет типизацию, но иначе. Разработан Facebook.

### Dart

`#Dart`

Dart - стоит особняком, потому что имеет собственный движок, работающий вне браузера (например, в мобильных приложениях). Первоначально был предложен Google, как замена JavaScript, но на данный момент необходима его транспиляция для запуска так же, как для вышеперечисленных языков.

### Angular

`#Angular`

Angular (версия 2 и выше) — это открытая и свободная платформа для разработки веб-приложений, написанная на языке TypeScript, разрабатываемая командой из компании Google, а также сообществом разработчиков из различных компаний. Angular — это полностью переписанный фреймворк от той же команды, которая написала AngularJS.

#### AngularJS

`#AngularJS`

AngularJS — JavaScript-фреймворк с открытым исходным кодом. Предназначен для разработки одностраничных приложений. Его цель — расширение браузерных приложений на основе MVC-шаблона, а также упрощение тестирования и разработки.

### RxJS

`#RxJS`

RxJS - это библиотека для работы с асинхронными и основанными на событиях программами с использованием наблюдаемых последовательностей.

Библиотека предоставляет основной тип Observable, несколько вспомогательных типов (Observer, Schedulers, Subjects) и операторы работы с событиями как с коллекциями (map, filter, reduce, every и подобные из JavaScript Array).

### Open Server

`#Open Server`

https://ospanel.io

Данная сборка многовариантная. Установка стационарная (на домашний компьютер) и портативная (на переносной носитель).

Open Server — сборка относительно молодая, однако прочно завоевывает первые позиции в линейке локальных серверов.

Причин в этом несколько, но главных три:

- Платформа портативна и доступна без установки на операционную систему;
- Open Server постоянно обновляется, и не «висит» по несколько лет без апгрейда, что говорит о постоянной работе автора над проектом;
- Платформа имеет пять языковых варианта (русский основной).

В сборке Open Server еще много приятных фишек, упрощающих работу разработчика. Радует простота установки, автономная подкачка недостающих программ, два сервиса HTTP (Apache и Nginx), несколько версий СУБД и PHP, наличие управляющей программы.

### Xampp

`#Xampp`

https://www.apachefriends.org/index.html

Данная сборка расшифровывается, как: любая ось+apache+mariabd+php+perl. Установка только стационарная.

Платформа Xampp лидирует в ранге аналогичных платформ, за рубежом. Платформа интересна, возможностью работы на разных операционных системах, об этом говорит первая буква акронима [X]. Это может быть Windows, Linux и OS X. Две буквы [p] в конце акронима, означают php и perl (доступные языки). Вместо MySQL стоит более мощная СУБД MariaDB.
Сообществу XAMPP более 10 лет, как следствие, много информации по использованию платформы. За XAMPP «ухаживают», постоянно обновляют, есть версия c PHP 7.0.4. даже появился русский вариант официального сайта.

### Electron JS

`#Electron JS`

https://www.electronjs.org

https://ru.wikipedia.org/wiki/Electron

Electron JS - Библиотека для создания оконных форм

Electron (ранее известен как atom shell) — фреймворк, разработанный GitHub. Позволяет разрабатывать нативные графические приложения для настольных операционных систем с помощью веб-технологий. Фреймворк включает в себя Node.js для работы с back-end и библиотеку рендеринга из Chromium.

https://youtu.be/gD50EhSJh-k

### Cleave.js

`#Cleave.js`

https://github.com/nosir/cleave.js

Cleave - автоматическое форматирование строки

### Next.js

`#Next.js`

```
npx create-next-app
```

Пример 1: localhost/create-next-app https://github.com/SpawnMetal/create-next-app https://youtu.be/_EOrSmjdOZQ

Пример 2: localhost/nextjs https://github.com/SpawnMetal/nextjs

Next.js — бесплатный и открытый JavaScript фреймворк, созданный поверх React.js для создания SSR-приложений.

Помогает создавать пользовательский интерфейс приложений (чаще всего, с помощью React, не придерживаясь его принципа — SPA (Single Page Application)).

SSR — принцип, используемый Next.js. Переводится с английского языка как «Отрисовка на стороне сервера». SSR помогает снизить нагрузку на устройство, ведь большинство операций производимых в приложении, происходит на сервере, а не на устройстве пользователя.

SSR также помогает улучшить SEO, так как в обычном подходе, который использует React (подход SPA), все отрисовывается на стороне клиента (браузера), поэтому код страниц подгружается когда пользователь заходит на страницу, но робот поисковых систем может только просмотреть изначальный код страницы, ещё не обработанный React.

SSR помогает избежать эту проблему изначальной загрузкой контента на всех страницах сайта.

- `<Link href=""><a>Текст</a></Link>`: реализует динамическую загрузку контента без перезагрузки страницы
  Папка pages - зарезервирована для создания страниц, адрес в строке сайта = названию файла
  filder/index.js - переход к странице в адресе folder, исполняющим файлом будет index.js
- `<style jsx global></style>`: для установки глобальных стилей, а не только для компонента. localhost/create-next-app/components/MainLayout.js

Пользовательский "Документ" pages/\_\_document.js для переосмысления и возможности переписать html документ https://nextjs.org/docs/advanced-features/custom-document

pages/\_\_app.js используется при инициализации страниц https://nextjs.org/docs/migrating/from-create-react-app

У error.module.scss после обработки next локализует стили за счёт .module в названии файла
next-env.d.ts - namespace описаны некоторые параметры для работы с next. `<reference types="next/types/global" />` означает, что ненужно импортировать React в те файлы, где используется jsx

getServerSideProps серверная функция. export default отрабатывает на сервере при открытии страницы в адресной строке для предварительной отрисовки - getServerSideProps + export default на клиенте и сервере. Переход на страницу из другой - getServerSideProps + export default только на клиенте

### Express

`#Express`

- `npm install express-validator`: An express.js middleware for validator. Для проверки полей на валидацию https://www.npmjs.com/package/express-validator

```
npm i express
```

https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction

Используется для роутинга, http-запросов, поднятия сервера и т. п.

Express.js, или просто Express, фреймворк web-приложений для Node.js, реализованный как свободное и открытое программное обеспечение под лицензией MIT. Он спроектирован для создания веб-приложений и API.

Де-факто является стандартным каркасом для Node.js.

### Node.js

`#Node.js`

https://Node.js.org/ru/

Node.js - программная платформа, основанная на движке V8 (транслирующем JavaScript в машинный код runtime), превращающая JavaScript из узкоспециализированного языка в язык общего назначения.

Однопоточен.

То, что Node.js разработан без потоков, не означает, что вы не можете использовать преимущества нескольких ядер в своей среде. Дочерние процессы могут быть созданы с помощью нашего child_process.fork() API, и с ними легко общаться. На основе того же интерфейса построен cluster модуль, который позволяет вам совместно использовать сокеты между процессами, чтобы обеспечить балансировку нагрузки между вашими ядрами. https://nodejs.org/en/about/

runtime - Значит, что если процесс в оперативке запущен, то он откликается на команды, иначе нет.

Документация по зависимостям https://Node.js.org/ru/docs/meta/topics/dependencies/

Пример проекта localhost/nodejs https://github.com/SpawnMetal/nodejs

- `node --version`: версия Node.js
- `node файл`: выполнение скрипта

Область видимости верхнего уровня в Node не является глобальной областью видимости

Сервер Node.js без фреймворка https://developer.mozilla.org/ru/docs/Learn/Server-side/Node_server_without_framework

SyntaxError: Cannot use import statement outside a module

Решение: Добавить в package.json "type": "module", чтобы заработал import

#### npm

`#npm`

https://www.npmjs.com

npm - node пакетный менеджер

https://habr.com/ru/post/133363/

- `npm init`: инициализировать проект, -y параметр для инициализации без вопросов. Затем npm i - установит все модули и зависимости из package.json, поэтому node_modules качать отдельно никому и никуда не нужно
- `npm run command`: команду получает из package.json параметр "scripts" текущей папки

Если npm run command "npm run start --prefix client", command находится в другой папке, то в команду добавляется --prefix с путём к папке client

Для запуска нескольких приложений, например клиента и сервера, в json используется параметр пакета concurrently: "dev": "concurrently \"npm run server\" \"npm run client\""

- `npm -v`: версия npm
- `npm install package_name`: установка пакета package_name локально. За место install можно просто i. Несколько пакетов перечисляются через пробел
- `npm install http-server -g`: установка пакета package_name глобально
- `npm show package_name version`: установленная версия пакета
- `npm view package_name version`: доступная версия пакета на сервере
- `npm view package_name`: информация о пакете
- `--save, --save-dev либо -D`: пакет установленный с помощью данного параметра, будет доступен только для разработки, добавлен в devDependencies

dependencies - зависимости, которые идут в package.json dependencies, затем если зайти в папку с данным названием внутри node_modules и открыть там package.json, то будут отображены другие установленные пакеты в dependencies и так далее по дереву.

- `npm uninstall package_name -g`:
- `npm i nodemon`: динамическое обновление сайта при внесении изменения в код, используется для разработки и запускается с помощью команды nodemon script.js

Предшествующее сообщение в консоли сервера: [nodemon] app crashed - waiting for file changes before starting...

Ошибка: Proxy error: Could not proxy request /api/auth/register from localhost:3000 to http://localhost:5000/

Решение: Не смог приконнектиться к БД, исправить доступ к БД и перезапустить сервер

- `npm i concurrently`: для одновременного запуска скриптов, например backend и frontend
- `npm i config`: пакет для работы с конфигурационным файлом. Создаётся папка config в которой default.json и production.json https://www.npmjs.com/package/config
- `npm i request-ip`: Получени ip клиента на сервере https://www.npmjs.com/package/request-ip
- `npm i ai-switcher-translit`: Смена раскладки и транслит https://github.com/alexanderkx/ai-switcher-translit
- `npm i bcryptjs`: Библиотека для шифрования / хеширования https://www.npmjs.com/package/bcryptjs
- `npm i jsonwebtoken`: #Токен jsonwebtoken библиотека для генерации веб-токенов JSON https://www.npmjs.com/package/jsonwebtoken
- `npm install materialize-css@next`: Materialize, Material Design https://materializecss.com/
- `npm i shortid`: Сокращение ссылок https://www.npmjs.com/package/shortid
- `npm install --save-dev cross-env`: Добавление кросс-операционных переменных для запуска скрипта, настройки прописываются у команд в package.json - scripts https://www.npmjs.com/package/cross-env
- `npm install -g json-server`: Поддельный REST API. Запуск сервера с db: json-server --watch db.json --port 4200 --delay 450 (сокращённо: json-server -w db.json -p 4200 -d 450) https://www.npmjs.com/package/json-server
- `npm i --save isomorphic-unfetch`: Серверный fetch https://www.npmjs.com/package/isomorphic-fetch
- `npm i nextjs-progressbar`: Индикатор загрузки https://www.npmjs.com/package/nextjs-progressbar

typescript typescriptreact
https://www.npmjs.com/package/typescript
https://www.npmjs.com/package/@types/react
npm install --save-dev typescript @types/react

- `npm install dotenv --save`: Dotenv - загружает переменные среды из .env файла process.env. `require('dotenv').config()` л ибо `import \* as dotenv from 'dotenv'`, затем `dotenv.config()`. https://www.npmjs.com/package/dotenv
- `npm i @material-ui/core`: #MaterialUI https://www.npmjs.com/package/@material-ui/core
- `npm i redux`: #Redux https://www.npmjs.com/package/redux
- `npm install react-redux`: Официальные привязки React для #Redux https://www.npmjs.com/package/react-redux
- `npm i redux-thunk`: #Redux #middleware для работы с асинхроном https://www.npmjs.com/package/redux-thunk
- `npm i redux-logger`: #Регистратор для #Redux https://www.npmjs.com/package/redux-logger
- `npm install redux-devtools-extension`: Расширение Redux DevTools. Например applyMiddleware, который позволяет диспатчить асинхроны. store = createStore(rootReducer, applyMiddleware(thunk, logger)) https://www.npmjs.com/package/redux-devtools-extension
- `npm i mobx mobx-react-lite`: MobX. Хранилище состояний, lite пакет для функциональных компонентов
  clipboard-copy
  `npm install clipboard-copy`: Копирование в буфер, подключать через require https://www.npmjs.com/package/clipboard-copy

##### Ошибки при установке пакета

###### 1

N:\web\htdocs_php5\php_site\files\11736>npm i --save-dev @babel/core @babel/cli

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@~2.3.1 (node_modules\chokidar\node_modules\fsevents):

npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.3.2: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

npm WARN interactive_instructions@1.0.0 No repository field.

npm ERR! Maximum call stack size exceeded

npm ERR! A complete log of this run can be found in:

npm ERR! C:\Users\kushkov-pa.ALPHA\AppData\Roaming\npm-cache_logs\2021-03-25T04_21_28_748Z-debug.log

Решение, обновить файл с зависимостями: npm i --package-lock-only

Если не поможет, удалить node_modules и заново установить все пакеты

###### 2

npm ERR! code ENOSELF

npm ERR! Refusing to install package with name "mobx" under a package

npm ERR! also called "mobx". Did you name your project the same

npm ERR! as the dependency you're installing?

Переименовать name в package.json, имя проекта не должно называться так же, как зависимость

#### npx

`#npx`

npx помогает нам избежать версий, проблем с зависимостями и установки ненужных пакетов, которые мы просто хотим попробовать.

Он также предоставляет простой и понятный способ выполнения пакетов, команд, модулей и даже списков и репозиториев GitHub.

- `npx package_name`: установка пакета с именем name локально
- `npm v create-react-app`: Вывод инфы о пакете и тегах dist-tags, например в списке будет next:
- `npx create-react-app@next sandbox`

npx временно установит следующую версию create-react-app, а затем запустит приложение и установит его зависимости.

После установки мы можем перейти к приложению следующим образом:

cd sandbox

и затем запустите его с помощью этой команды: `npm start`

Зачастую асинхронные методы из установленных пакетов пишутся без приписки Sync

В callback первый параметр всегда является содержанием информации об ошибке

### Emmet

`#Emmet`

https://emmet.io/

Emmet (ранее Zen Coding) — набор плагинов для текстовых редакторов, которые в некоторой степени ускоряют написание кода HTML, XML, XSL, а также кода на некоторых других языках.

```JSON
"emmet.includeLanguages": {
  "javascript": "javascriptreact"
}
```

### JSON Web Token (JWT)

`#JWT`

JSON Web Token (JWT) — это открытый стандарт (RFC 7519) для создания токенов доступа, основанный на формате JSON. Как правило, используется для передачи данных для аутентификации в клиент-серверных приложениях.

Токены создаются сервером, подписываются секретным ключом и передаются клиенту, который в дальнейшем использует данный токен для подтверждения своей личности.

`#LocalStorage` Хранить можно в LocalStorage (удалить можно с помощью js), чтобы после рестарта системы получать его заново https://developer.mozilla.org/ru/docs/Web/API/Window/localStorage

`#SessionStorage` очищает данные при закрытии браузера

### Монорепозитории

`#Монорепозитории`

Монорепозитории NX и Lerna, или Туда и обратно https://habr.com/ru/post/520186/

#### Nx

`#Nx`

https://nx.dev/getting-started/intro

Nx — это интеллектуальная, быстрая и расширяемая система сборки с первоклассной поддержкой монорепозиториев и мощными интеграциями.

NX использует для сборки webpack, в связи с чем это приводит к куче ошибок и долгой сборке.

Так же сам NX сильно засоряет проект кучей ненужных файлов, в целом не актуальен.

#### Lerna

`Lerna`

https://lerna.js.org/

Lerna — это быстрая современная система сборки для управления и публикации нескольких пакетов JavaScript/TypeScript из одного репозитория.

Имеет свои весомые недостатки

#### Rush

https://rushjs.io/

Rush - масштабируемый менеджер монорепозиториев для Интернета от Microsoft

### NestJS

`#NestJS`

https://nestjs.com

https://youtu.be/abdgy72csaA

Nest (NestJS, фреймворк) — это платформа для создания эффективных, масштабируемых серверных приложений Node.js.

Под капотом Nest использует надежные платформы HTTP-серверов, такие как Express (по умолчанию), и при желании также может быть настроен для использования Fastify!

- `CRUD-генератор` https://docs.nestjs.com/recipes/crud-generator#crud-generator
- `nest g resource Name` - Команда не только генерирует все строительные блоки NestJS (модуль, служба, классы контроллера), но также класс сущности, классы DTO, а также .spec файлы тестирования
- `nest g mo Name` - Создаёт модель
- `nest g co Name` - Создаёт контроллер
- `nest g s Name` - Создаёт сервис

@nestjs/config - для работы с .env

ConfigModule необходимо импортировать в модуле

ConfigModule.forRoot() - если .env в корне проекта - глоабльный каталог

Пример: localhost\nestjs-crash-course-main

Декортаторы маршрутов и параметров: https://docs.nestjs.com/custom-decorators

Например @Body, @Query, @Param

Пример: @Body('id') id

@Get(':id'), затем @Param('id') id

```
npm i @nestjs/mongoose mongoose
```

#### Injectable

По сути он добавляет сервис в контекст контроллера, делая все методы сервиса static и позволяет обращаться к ним без использования инсты: this.appService.serviceMethod() и связывает механизмы под капотом.

#### Injection scopes

`#Injection`

https://docs.nestjs.com/fundamentals/injection-scopes

Поставщик может иметь любую из следующих областей действия:

- `DEFAULT` - Один экземпляр поставщика является общим для всего приложения. Время жизни экземпляра напрямую связано с жизненным циклом приложения. После начальной загрузки приложения создаются экземпляры всех одноэлементных провайдеров. Область Singleton используется по умолчанию.
- `REQUEST` - Новый экземпляр провайдера создается исключительно для каждого входящего запроса . Экземпляр удаляется сборщиком мусора после завершения обработки запроса.
- `TRANSIENT` - Временные поставщики не распределяются между потребителями. Каждый потребитель, внедряющий временного поставщика, получит новый выделенный экземпляр.

#### AdminJS

`#AdminJS`

Админка БД https://www.npmjs.com/package/@adminjs/nestjs

AdminJS & Express: NodeJS admin panel setup in 4 minutes https://youtu.be/R613IRVDLJ0

### GraphQL

`#GraphQL`

https://graphql.org/

https://habr.com/ru/post/326986/

https://docs.github.com/en/graphql/overview/about-the-graphql-api

Все о GraphQL за 30 минут https://youtu.be/7zEaHr_iJjA
Full-stack приложение. NestJS TypeORM PostgreSQL GraphQL Docker. Часть 1. Backend https://youtu.be/msVhfCzFWvY

GraphQL — язык запросов данных и язык манипулирования данными с открытым исходным кодом для построения веб ориентированных программных интерфейсов. GraphQL был разработан как внутренний проект компании Facebook
mutation выполняются последовтельно, а query параллельно

### Контейнеризация

#### Docker

`#Docker`

https://www.docker.com/

https://javarush.com/groups/posts/3793-kto-takie-docker-kubernetes-openshift-i-kak-oni-mezhdu-soboy-svjazanih

Docker — программное обеспечение для автоматизации развёртывания и управления приложениями в средах с поддержкой контейнеризации, контейнеризатор приложений. Позволяет «упаковать» приложение со всем его окружением[en] и зависимостями в контейнер, который может быть развёрнут на любой Linux-системе с поддержкой контрольных групп в ядре, а также предоставляет набор команд для управления этими контейнерами.

Для одновременного управления пачкой контейнеров используется Docker Compose который входит состав Docker.

`docker compose up`: запустить
`docker ps`: запущенные контейнеры

https://www.docker.com/

Зачем нужен и как работает Docker — ликбез https://youtu.be/KS80Knz-1Z4

`#Wasm #WebAssembly`

https://docs.docker.com/desktop/wasm/

Wasm (сокращение от WebAssembly) — это более быстрая и легкая альтернатива контейнерам Linux и Windows, которые вы используете в Docker

### Оркестрация

`#Оркестрация`

В промышленной разработке есть необходимость «упаковки» приложения, этот подход особенно актуален в микросервисной архитектуре.
Контейнеры — это основное средство для «упаковки» приложений. Контейнерами занимается Docker, создает образы контейнеров, поднимает и перемещает контейнеры. Для одновременного управления пачкой контейнеров используется Docker Compose который входит состав Docker. Эти программы – являются свободно распространяемым ПО.
Kubernetes(K8s) – инструмент для оркестровки контейнеризированных приложений — автоматизации их развёртывания, масштабирования и координации в условиях кластера. Поддерживает основные технологии контейнеризации, включая Docker. K8s является открытым(open-source) программным обеспечением.
OpenShift это надстройка над Kubernetes, предлагающая дополнительные функции. Это платный продукт, в отличие от K8s предназначенный для корпоративного использования. Предоставляет DevOps из «коробки»: поддержка основных сценариев развертывания blue/green, canary, имеет встроенную поддержку Jenkins и предоставляет удобные инструменты для администрирования и работы с кластером. Имеет более строгую модель безопасности и встроенный мониторинг.

#### Kubernetes

`#Kubernetes`

Kubernetes — это платформа с открытым исходным кодом для управления контейнеризированными рабочими нагрузками и сервисами.

https://kubernetes.io/ru/docs/concepts/overview/what-is-kubernetes/

https://javarush.com/groups/posts/3793-kto-takie-docker-kubernetes-openshift-i-kak-oni-mezhdu-soboy-svjazanih

Что такое Kubernetes за 9 минут https://youtu.be/ZI7w6ZeBI8k

Сложен в использовании, но более гибкий. Почему Docker Swarm, а не Kubernetes? https://youtu.be/mR0Xk_lyC48

Kubernetes — это не просто система оркестрации. Фактически, Kubernetes устраняет необходимость в этом. Техническое определение оркестрации — это выполнение определенного рабочего процесса: сначала сделай A, затем B, затем C. Напротив, Kubernetes содержит набор независимых, компонуемых процессов управления, которые непрерывно переводит текущее состояние к предполагаемому состоянию. Неважно, как добраться от А до С. Не требуется также централизованный контроль. Это делает систему более простой в использовании, более мощной, надежной, устойчивой и расширяемой.

`#Helm Charts`

https://helm.sh/

Упаковщик для Kubernetes. Множество файлов с настройками упаковывает в один, чтобы можно было задеплоить приложухи с разными настройками разом

Helm Charts - Что это такое и зачем нужно - За 5 минут! https://youtu.be/vWZZjoILeos

#### OpenShift

`#OpenShift`

Более популярный

https://www.redhat.com/en/technologies/cloud-computing/openshift

https://javarush.com/groups/posts/3793-kto-takie-docker-kubernetes-openshift-i-kak-oni-mezhdu-soboy-svjazanih

[OpenShift] Урок-5. Зачем нужен OpenShift https://youtu.be/2QV9AO4YDNk

OpenShift это надстройка над Kubernetes, предлагающая дополнительные функции
Он сразу же готов к использованию, его не надо долго и мучительно настраивать, можно немедленно пускать в продакшн.
Смотрите сколько всяких иконок, над Kubernetes. И каждая из них делает свои крутые штуки.

- Это платный продукт, в отличие от K8s;
- DevOps из «коробки», поддержка основных сценариев развертывания blue/green, canary;
- Встроенная поддержка Jenkins;
- Предоставляет удобные инструменты для администрирования и работы с кластером;
- Имеет более строгую модель безопасности и встроенный мониторинг.

https://www.okd.io/

OKD, построенный на основе упаковки контейнеров OCI и управления кластером контейнеров Kubernetes, также дополнен функциями управления жизненным циклом приложений и инструментами DevOps. OKD предоставляет полную платформу контейнерных приложений с открытым исходным кодом.

#### Docker Swarm

`#Swarm`

Почему Docker Swarm, а не Kubernetes? https://youtu.be/mR0Xk_lyC48

Docker Swarm (или режим роя Docker) — это инструмент оркестрации контейнеров, подобный Kubernetes. Он позволяет управлять несколькими контейнерами, развернутыми на нескольких хостах, на которых запущен сервер Docker. По умолчанию режим роя отключен; его должна настроить команда DevOps.

#### Portainer

`#portainer`

UI https://www.portainer.io/

Универсальное программное обеспечение для управления контейнерами

#### Atlassian Compass

`#сompass`

Compass и оркестрация контейнеров

https://www.atlassian.com/software/compass

Независимо от того, какое решение для оркестрации контейнеров вы выберете, важно использовать подходящий инструмент, чтобы управлять сложностью распределенной архитектуры по мере масштабирования. Atlassian Compass — это расширяемая платформа для разработчиков, которая объединяет разрозненные сведения о результатах разработки и совместной работе команд в едином центре с возможностью поиска. Compass не только поддержит вас в борьбе с разрастанием микросервисов с помощью каталога компонентов. Это решение поможет внедрить передовые методы и оценить работоспособность вашего ПО, используя карты оценки, а также снабдит данными и аналитикой по всему пакету инструментов DevOps с помощью расширений на платформе Atlassian Forge.

### TypeORM

`#TypeORM #ORM`

```
npm install --save @nestjs/typeorm typeorm pg
```

https://typeorm.io/

Объектно-реляционное отображение (ORM) — это мост между API и базой данных

ORM (англ. Object-Relational Mapping, рус. объектно-реляционное отображение, или преобразование) — технология программирования, которая связывает базы данных с концепциями объектно-ориентированных языков программирования, создавая «виртуальную объектную базу данных». Существуют как проприетарные, так и свободные реализации этой технологии.

TypeORM — это ORM, который может работать на платформах NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo и Electron и может использоваться с TypeScript и JavaScript (ES5, ES6, ES7, ES8). Его цель — всегда поддерживать новейшие функции JavaScript и предоставлять дополнительные функции, помогающие разрабатывать любые приложения, использующие базы данных — от небольших приложений с несколькими таблицами до крупномасштабных корпоративных приложений с несколькими базами данных.

TypeORM поддерживает шаблоны Active Record и Data Mapper, в отличие от всех других существующих в настоящее время JavaScript ORM, что означает, что вы можете писать высококачественные, слабосвязанные, масштабируемые, удобные в сопровождении приложения наиболее продуктивным способом.

TypeORM находится под сильным влиянием других ORM, таких как Hibernate, Doctrine и Entity Framework.

Понятие о миграциях: https://medium.com/nuances-of-programming/%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D0%B5-%D0%BE-%D0%BC%D0%B8%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D1%8F%D1%85-%D0%B2-typeorm-9a6a40ddd76e

Relation options, cascades https://typeorm.io/relations#relation-options

- `@OneToOne(() => Entity)` https://typeorm.io/decorator-reference#onetoone

`entityName: Entity`

A может иметь только один B и наоборот, который указывается в колонке nameId

Обязателен @JoinColumn иначе будут ошибки, например при find

У таблицы B связь с текущей A не обязательна

- `@ManyToOne(() => Entity)` https://typeorm.io/decorator-reference#manytoone

`entityName: Entity`

У текущих A (Photo) может быть один и тот же B (User), который указывается в колонке nameId

Не нужен @JoinColumn, nameId создаётся автоматом

У обеих таблиц можно применить @ManyToOne, но при find будет выводить только одного

- `@OneToMany(() => Entity, entityName => entityName.b)` https://typeorm.io/decorator-reference#onetomany

`entityNames: Entity[]`

У текущего A (User) может быть много B[] (Photo[])

nameId в A не создаётся, он их получает из связанной

В find получим массив B

- `@ManyToMany(() => Entity)` https://typeorm.io/decorator-reference#manytomany https://typeorm.io/many-to-many-relations#many-to-many-relations-with-custom-properties

`@JoinTable({name: 'b_a'})`

`entityNames: Entity[]`

У A (Question) может быть много B (Category) и наоборот

Соединительная таблица генерируется автоматом, поэтому @JoinTable обязателен, а в текущей таблице формироваться колонка с id не будет

Можно задать свои настройки имени таблицы и колонок соединения:

- @JoinTable https://typeorm.io/decorator-reference#jointable

Обязателен для @ManyToMany

Если в таблице связей нужна дополнительная колонка, то entity создаётся отдельно

```js
@JoinTable({
  name: "question_categories", // table name for the junction table of this relation
  joinColumn: {
    name: "question",
    referencedColumnName: "id"
  },
  inverseJoinColumn: {
    name: "category",
    referencedColumnName: "id"
  }
})
```

- `@JoinColumn` https://typeorm.io/decorator-reference#joincolumn

Создаёт колонку со связанным nameId

Обязателен у @OneToOne

Не нужен у @ManyToOne

- `@RelationId(b: B, b => b.a)` https://typeorm.io/decorator-reference#relationid

aId: number[]

Не создаёт колонку

В find выведет массив со связанными a.id

### Meteor

`#Meteor`

https://www.meteor.com/

https://ru.wikipedia.org/wiki/Meteor_(веб-фреймворк)

Устаревающая технология для создания FullStack-приложений, не актуально.

Meteor — это платформа с открытым исходным кодом для беспрепятственного создания и развертывания веб-приложений, мобильных и настольных приложений на Javascript.

Meteor — веб-платформа на языке JavaScript, предназначенная для разработки Web-приложений реального времени. Для связи с современными браузерами используется протокол Distributed Data Protocol (DDP), поддерживаемый с помощью WebSocket'ов, либо, если поддержки веб-сокетов и DDP нет — AJAX.

Код Meteor работает поверх node.js (однако он не придерживается принятой в node.js асинхронной модели, что может затруднить интеграцию node.js и meteor-приложений)[1]. Ядром Meteor является протокол DDP[2]. Он предназначен для работы с коллекциями JSON-документов, позволяя легко создавать, обновлять, удалять, запрашивать и просматривать их. По умолчанию в качестве хранилища таких документов используется MongoDB.

### WebSocket

`#WebSocket`

```
npm i ws
```

Разница между веб-сокетами и Socket.IO https://habr.com/ru/post/498996/

Веб-сокеты это продвинутая технология, позволяющая открыть постоянное двунаправленное сетевое соединение между браузером пользователя и сервером. С помощью его API вы можете отправить сообщение на сервер и получить ответ без выполнения http запроса, причём этот процесс будет событийно-управляемым.

- Что такое Websocket? Websockets простыми словами https://youtu.be/SxMvxIHBahU
- Знакомство с WebSocket https://youtu.be/DKOaL94VyFY
- https://learn.javascript.ru/websocket
- https://developer.mozilla.org/ru/docs/Web/API/WebSockets_API
- https://ru.wikipedia.org/wiki/WebSocket
- https://www.npmjs.com/package/ws

#### Socket.IO

`#Socket.IO`

https://socket.io/

Разница между веб-сокетами и Socket.IO https://habr.com/ru/post/498996/

Socket.IO — JavaScript-библиотека для веб-приложений и обмена данными в реальном времени. Состоит из двух частей: клиентской, которая запускается в браузере и серверной для node.js. Оба компонента имеют похожее API. Подобно node.js, Socket.IO событийно-ориентированная.

Socket.IO главным образом использует протокол WebSocket, но если нужно, использует другие технологии, например Flash Socket, AJAX Long Polling, AJAX Multipart Stream, предоставляя тот же самый интерфейс. Помимо того, что Socket.IO может быть использована как оболочка для WebSocket, она содержит много других функций, включая вещание на несколько сокетов, хранение данных, связанных с каждым клиентом, и асинхронный ввод/вывод.

### Markdown

`#Markdown #md`

- https://daringfireball.net/projects/markdown/
- https://gist.github.com/Jekins/2bf2d0638163f1294637
- https://lifehacker.ru/chto-takoe-markdown/

Облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).

### JSDoc

`#JSDoc`

JSDoc — генератор документации в HTML-формате из комментариев исходного кода на JavaScript.

ОФФ https://jsdoc.app/

Source https://github.com/jsdoc/jsdoc

https://ru.wikipedia.org/wiki/JSDoc

https://youtu.be/YK-GurROGIg

См. jsdoc_example

npm run doc - скомпилировать в папку out, название папки можно сменить

В jsdoc.json нужно указать у "source": {"include": ["src"]}, иначе не увидит содержимое папки src

В "opts" можно указать путь к папке с туториалами и файл редми, содержимое которого отобразится на главной

### Инструменты CI CD

`#CI #CD`

см [CI CD](#CI-CD)

#### Jenkins

`#Jenkins #Pipeline`

https://www.jenkins.io/

Ведущий сервер автоматизации с открытым исходным кодом, Jenkins предоставляет сотни подключаемых модулей для поддержки создания, развертывания и автоматизации любого проекта.

Популярный и универсальный

В Jenkinsfile описываются команды с действиями, в web адмике он указывается в разделе Configureб затем Build Now запускает его.

Jenkins - Автоматизация CI/CD - Полный Курс на Простом Языке https://youtu.be/cyb10iplv7U

Jenkins Pipeline (или просто «Pipeline» с большой буквы «P») — это набор плагинов, которые поддерживают реализацию и интеграцию конвейеров непрерывной доставки в Jenkins. https://www.jenkins.io/doc/book/pipeline/

#### Bamboo

`#Bamboo`

https://www.atlassian.com/ru/software/bamboo

Bamboo — это сервер непрерывной интеграции от Atlassian

#### TeamCity

`#TeamCity`

https://www.jetbrains.com/ru-ru/teamcity/

TeamCity — серверное программное обеспечение от компании JetBrains, билд-сервер для обеспечения непрерывной интеграции.

#### GitLab CI CD

`#GitLab`

https://gitlab.com/

Популярный, простой и универсальный. Если проект на GitLab, то проще использовать GitLab CI/CD

GitLab — веб-инструмент жизненного цикла DevOps с открытым исходным кодом, представляющий систему управления репозиториями кода для Git с собственной вики, системой отслеживания ошибок, CI/CD пайплайном и другими функциями.

#### CircleCI

`#CircleCI`

https://circleci.com/

CircleCI — это платформа непрерывной интеграции и непрерывной доставки, которую можно использовать для реализации методов DevOps

### pandas

`#pandas`

pandas — программная библиотека на языке Python для обработки и анализа данных.

Основная область применения — обеспечение работы в рамках среды Python не только для сбора и очистки данных, но для задач анализа и моделирования данных, без переключения на более специфичные для статобработки языки (такие, как R и Octave).

Очень быстрая библиотека для работы с БД.

## Stacks

### MERN

`#MERN`

Стек MERN - это JavaScript-стек, разработанный для упрощения процесса разработки. MERN включает в себя четыре компонента с открытым исходным кодом: [MongoDB](#MongoDB), [Express](#Express), [React](#React) и [Node.js](#Node.js).

Пример localhost\mern-course https://github.com/SpawnMetal/mern-course

https://youtu.be/ivDjWYcKDZI

Локально находится в папке mern-course

Запуск клиента и сервера для разработки: npm run dev

**Публикация на хостинге:**

Домен взят на https://2domains.ru

Хостинг, прост в настройках и поддерживает node, взят на https://vscale.io

Рекомендованная ОС - Ubuntu

512 МБ ОЗУ - мало, нужно больше

Через SSH Putty ходим, обновляем всё ПО sudo apt update, ставим Git, клонируем, гуглим установку Node.js

npm run client:install - установит node_modules для клиента

Билдим клиент npm run client:build

Настроить config/production.json на хостинге

Настроить в админке мерна ip сервера для доступа к БД

Чтобы при закрытии консоли сервер не вырубался ставим глобально npm install pm2 -g

Запускаем находясь в папке с проектом: pm2 start npm -- start

Material Design ставится соответственно в папку client
"proxy": "http://localhost:5000", прописывается в client/package.json, чтобы запросы с клиента шли по серверной ссылке, на сервер, а не на клиент

## Flux-архитектура

`#Flux-архитектура #State #Manager #Менеджер #Состояний`

https://ru.wikipedia.org/wiki/Flux-%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0

`Flux-архитектура` — архитектурный подход или набор шаблонов программирования для построения пользовательского интерфейса веб-приложений, сочетающийся с реактивным программированием и построенный на однонаправленных потоках данных.

Согласно замыслу создателей и несмотря на то, что Facebook предоставил реализацию Flux в дополнение к React, Flux не является ещё одним веб-фреймворком, а является архитектурным решением.

### MobX

`#MobX`

https://mobx.js.org/README.html

Принципы https://hackernoon.com/the-fundamental-principles-behind-mobx-7a725f71f3e8

Ограничения https://mobx.js.org/observable-state.html#limitations

Для реализации архитектуры flux используется библиотека MobX.

`Флюс` - архитектурное решение, описывающее подход однонаправленных потоков данных.

`MobX` - javascript библиотека, реализующая архитектуру flux.

Пример с React: localhost\test_with_questions https://github.com/SpawnMetal/test_with_questions

Пример из документации: localhost\mobx_node https://github.com/SpawnMetal/mobx_node

https://mobx.js.org/observable-state.html

`makeObservable` для явного указания свойств. Подкласс или суперкласс должен содержать его.

`makeAutoObservable` для автоопределения свойств, поддерживает только те свойства, которые уже определены. Его нельзя использовать в классах, которые имеют super или являются подклассами.

`observable` - в отличие от makeObservable, observable поддерживает добавление (и удаление) полей в объект. Это observable отлично подходит для коллекций, таких как объекты с динамическим ключом, массивы, карты и наборы.

`untracked`: речь не идет о необнаруживаемой записи. Вместо этого он просто приводит к тому, что чтение не отслеживается. Другими словами, это способ сказать, что мы не заинтересованы в будущих обновлениях данных, которые мы используем.

Например transaction, никто не использует этот API на практике, но это механизм, встроенный в действия, потому что концептуально он имеет большой смысл: действия выполняются в ответ на (пользовательское) событие, а не в ответ на изменения состояния, поэтому они не должны отслеживание того, какие данные они потребляют. Для этого и нужны реакции.

Правила вывода: https://mobx.js.org/observable-state.html

- Все собственные свойства становятся `observable`.
- Все getтеры становятся `computed`.
- Все setтеры становятся `action`.
- Все функции на прототипе делаются `autoAction`.
- Все функции генератора на прототипе становятся `flow`. (Обратите внимание, что функции генератора не обнаруживаются в некоторых конфигурациях транспиляторов, если поток не работает должным образом, обязательно укажите это `flow` явно.)
  Члены, отмеченные `false` в `overrides` аргументе, не будут аннотированы. Например, используя его для полей только для чтения, таких как идентификаторы.

`observable Map, Set, Array + autorun`: https://mobx.js.org/observable-state.html
Автоматически наблюдает за изменением autorun и кэширует состояние, если оно не изменилось, то autorun не будет вызван. https://mobx.js.org/computeds.html#example
Он также запускается один раз при создании самого себя. https://mobx.js.org/reactions.html#autorun
Он реагирует только на изменения в наблюдаемом состоянии, на вещи, которые вы аннотировали observable или computed.
Autorun отслеживает только те наблюдаемые, которые считываются во время синхронного выполнения предоставленной функции, но не отслеживает ничего, что происходит асинхронно. https://mobx.js.org/reactions.html#rules

Наблюдаемые массивы имеют несколько дополнительных полезных функций:

- `clear()`: удаляет все текущие записи из массива.
- `replace(newItems)`: заменяет все существующие записи в массиве новыми.
- `remove(value)`: удаляет один элемент по значению из массива. Возвращает true, если элемент был найден и удален.

`reaction`: похож на autorun, но дает более точный контроль над тем, какие наблюдаемые объекты будут отслеживаться. https://mobx.js.org/reactions.html#reaction

`when`: наблюдает и выполняет данную функцию предиката, пока она не вернет true. Как только это происходит, данная функция эффекта выполняется, и автозапуск уничтожается. https://mobx.js.org/reactions.html#when

Правила computed https://mobx.js.org/computeds.html#rules

- Они не должны иметь побочных эффектов или обновлять другие наблюдаемые.
- Избегайте создания и возврата новых наблюдаемых.
- Они не должны зависеть от ненаблюдаемых значений.

`MobX` не может сделать примитивные значения наблюдаемыми, поскольку они неизменяемы в JavaScript (но их можно упаковать). Хотя обычно этот механизм не используется вне библиотек. https://mobx.js.org/observable-state.html

Экземпляры класса никогда не станут наблюдаемыми автоматически путем передачи их свойству observableили их присвоения . observableСоздание наблюдаемых членов класса считается обязанностью конструктора класса. https://mobx.js.org/observable-state.html

По умолчанию не разрешено изменять состояние вне `action`.

Аннотацию `action` следует использовать только для функций, предназначенных для изменения состояния. Функции, которые извлекают информацию (выполняют поиск или фильтруют данные), не должны быть помечены как действия, чтобы позволить MobX отслеживать их вызовы.

Генератору ставить flow вместо action. https://mobx.js.org/actions.html#using-flow-instead-of-async--await-

`flow.bound`: https://mobx.js.org/actions.html#flowbound

`cancel()`: прервёт работающий генератор и отменит его. Любые пункты try / finally будут по-прежнему выполняться.

`action.bound`: https://mobx.js.org/actions.html#actionbound

Аннотацию action.bound можно использовать для автоматической привязки метода к правильному экземпляру, чтобы this он всегда правильно связывался внутри функции.

`makeAutoObservable(this, {}, {autoBind: true})`

`runInAction(fn)`: Используйте эту утилиту для создания временного действия, которое вызывается немедленно. Может быть полезен в асинхронных процессах.

Отключение обязательных actions. Например во время тестирования https://mobx.js.org/actions.html#disabling-mandatory-actions-

Очистка памяти https://mobx.js.org/reactions.html#always-dispose-of-reactions

Обратите внимание, что мы возвращаем средство удаления, созданное autorunиз нашей функции эффекта. Это важно, так как гарантирует autorunочистку после размонтирования компонента! См Совет: useEffect и наблюдаемые объекты https://mobx.js.org/react-integration.html#tips

Подкомпоненты observer компонента, тоже должны быть обёрнуты в observer https://mobx.js.org/react-integration.html#always-read-observables-inside-observer-components https://mobx.js.org/react-integration.html#dont-pass-observables-into-components-that-arent-observer

Если observer используется в контексте рендеринга на стороне сервера; обязательно вызовите enableStaticRendering(true), чтобы observer он не подписывался на какие-либо используемые наблюдаемые, и не возникало проблем с GC.

Используйте такие утилиты, как `isObservable`, `isObservableProp` если необходимо `проверить` `Observable` во время выполнения.

### Redux

`#Redux`

Устаревшая, усложнённая технология с абсурдной реализацией, загрязняющая проект, на смену которой пришёл MobX. Не использовать Redux ни в коем случае!!!

https://redux.js.org/

Predictable State Container for JS Apps (Контейнер предсказуемого состояния для JS-приложений)

Redux — библиотека для JavaScript с открытым исходным кодом, предназначенная для управления состоянием приложения. Чаще всего используется в связке с React или Angular для разработки клиентской части. Содержит ряд инструментов, позволяющих значительно упростить передачу данных хранилища через контекст.

Redux – библиотека с простым API, предсказуемое хранилище состояния приложений.

Пример 1: localhost\react-redux-course https://github.com/SpawnMetal/react-redux-course https://youtu.be/G3GGXIhggGs
Пример 2: localhost\redux https://github.com/SpawnMetal/redux https://youtu.be/YdYyYMFPa44

Redux не привязан к фреймворку, это технология для разделения данных и способа отображения.

Всё состояние приложения - это единый объект в Redux.

Component -> Action -> Store -> Reducer -> Store -> Component

Component / View общается со Store через Action

- `Action`: объект с типом действия, который диспатчится в Store

- `Store`: содержит само состояние, которое меняется через Reducer

- `Reducer`: это чистая функция, которая вычисляет следующее состояние на основании предыдущего.

`Reducer правила`: всегда должна вернуть state, если action.type совпадает с тем, что мы меняем в Reducer, тогда мы должны вернуть новый объект - это иммутабельность (неизменный объект).

Затем в Store отрабатывает observer / subscribers, обновляя тем самым Component

`Store`

https://redux.js.org/api/store

- `getState()`: Получить состояние
- `dispatch(action)`: Изменить состояние
- `subscribe(listener)`: Подписаться на обновления
- `replaceReducer(nextReducer)`: Заменить редьюсер

createStore -> Reducer switch(action.type) case CREATE_POST -> return всте старые state в Store и новый state(Store)

В action есть dispatch

const dispatch = `useDispatch()` // Позволяет диспатчить (записывать) action в store

В dispatch передаётся {type: action}

dispatch вызывает `Reducer` из `createStore` в котором вычисляется новый state(Store)

const loading = `useSelector(state => state.app.loading)` // Получить значение из state

connect(f(state) return {key: state...}, {{type: action}, ...})(Component) arg1: Преобразовывает стейты в пропсы. arg2: Сработает диспатч

Функция connect возвращает функцию, тот же самый компонент, но уже с дополнительным функционалом

### Effector

`#Effector`

https://effector.dev/ru/

Отечественная попытка реализовать собственный стейт менеджер. Абсолютно нет ни малейшей необходимости этого делать, так как MobX отлично справляется со своей задачей. Так же Effector, как и Redux загрязняет проект, делая код не экологичным. Не использовать!

## Автотесты

`#Автотесты`

Автоматизированное тестирование (Автотест) – это когда тесты написаны отдельно от кода, и можно в любой момент запустить их и проверить все важные случаи использования.

https://habr.com/ru/post/336030/

Принципы: https://habr.com/ru/company/mailru/blog/466879/

https://medium.com/@andr.ivas12/%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B4%D0%BB%D1%8F-%D1%87%D0%B0%D0%B9%D0%BD%D0%B8%D0%BA%D0%BE%D0%B2-c007d43da791

Список фреймворков для тестов https://en.wikipedia.org/wiki/List_of_unit_testing_frameworks#JavaScript

### Виды тестирования

Виды тестирования (критерий — степень изолированности кода). Тестирование бывает

- `Блочное (Unit testing)`: тестирование одного модуля в изоляции. https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D0%B4%D1%83%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5
- `Интеграционное (Integration Testing)`: тестирование группы взаимодействующих модулей. Ломает ли новый код уже созданный ранее. https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%BE%D0%B5_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5
  В верхней части находятся тесты пользовательского интерфейса (end to end) Они действуют так же, как конечный пользователь работает с приложением. Запускаем очень редко — несколько раз за проект. Работают очень медленно.
- `Системное (System Testing)`: тестирование системы в целом. https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%BD%D0%BE%D0%B5_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5

- `Sociable (общительный) тест`: это тест который использует реальные методы (или классы), которые входят в тестируемую единицу. Например, вы тестируете метод «цена» из класса заказов.
  Методу «цена» необходимо вызвать методы из класса клиент и продукт. В данном виде тестов будут вызваны именно эти методы, и ошибка в этих методах приведет к ошибке теста. Методы из классов клиент и продукт называется партнеры (collaborators).
- `Solitary (одинокий) тест`: это тест, который в качестве партнеров использует дубли (TestDouble). Тест-дубли — это общий термин для любого случая, в котором вы заменяете реальный объект, исключительно для целей тестирования.
- `BDD (Behaviour Driven Development)`: или разработка на основе поведения, появилось в процессе эволюции unit-тестирования

Там используются все те же правила, что и в TDD: тест, код, рефакторинг. Отличие заключается в том, что BDD охватывает более широкую публику. Спецификации становятся доступными не только программистам, но и людям,
не разбирающимся в коде, но имеющим отношение к разработке ПО. Таким образом, в процесс создания тестов подключается вся команда: аналитики, тестеры, менеджеры.

- `TDD (Test-Driven Development)`: или разработка через тестирование, как часть экстремального программирования. Эта техника для построения ПО, которая управляет процессом разработки через написание тестов.

В сущности, повторяет три простых правила:

- Сначала пишется тест

- Затем пишется код под этот тест

- Рефакторинг нового и старого кода, чтобы улучшить качество кода

В качестве детектора ошибок или автоматических тестов, выступают не только `unit-тесты`, но также интеграционные тесты, и другие автоматические тесты. Но `unit-тесты` здесь играют основу, т.к. написать их просто и выполняются они очень быстро.

- `Высокоуровневые тесты`: это вторая линия обороны. Если вы получили ошибку в высокоуровневом тестировании, то это не просто ошибка в коде, это отсутствующий или некорректный юнит тест!

### Принципы тестирования

Простой и аккуратный код, читаемый в одну строку, как будто разговорная речь. Задумываться нельзя при взгляде на него.

Название формируется из правил:

- Что именно тестируется? Например, метод ProductsService.addNewProduct.
- При каких условиях и сценарии? Например, методу не передаётся цена.
- Какой ожидается результат? Например, новый продукт не одобрен.

Паттерн `AAA`:

- Каждый тест должен состоять из трёх чётко разделённых разделов:
- Arrange (подготовка)
- Act (действие)
- Assert (результат)

Если используется сложный код, то необходимо расширить сопоставитель самому https://jestjs.io/docs/en/expect#expectextendmatchers

Метод `чёрного ящика`:

- Придерживайтесь тестирования по методу "чёрного ящика": тестируйте только публичные методы. Этот подход также называют поведенческим тестированием.
- С другой стороны, если вы тестируете внутренности (метод «белого ящика»), то вместо планирования выходных данных компонентов вы сосредоточитесь на мелких подробностях,
  и ваши тесты могут сломаться из-за мелких переделок кода, пусть даже с результатами всё будет в порядке, а на сопровождение будет уходить гораздо больше ресурсов.

`#Mock-объект`

Mock-объект - фальшивый объект, накрученный объект на другой (клон, эмулирующий), как JQuery, но только для тестов, например подключение с помощью Ajax к серверу. Ожидает в отличие от стаба (stub - заглушка), который просто имитирует.

Mock-объект (от англ. mock object, буквально: «объект-пародия», «объект-имитация», а также «подставка») — в объектно-ориентированном программировании — тип объектов, реализующих заданные аспекты моделируемого программного окружения.

Mock-объект представляет собой конкретную фиктивную реализацию интерфейса, предназначенную исключительно для тестирования взаимодействия и относительно которого высказывается утверждение.

https://ru.wikipedia.org/wiki/Mock-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82

### Jest

`#Jest`

Jest - автотесты, файлы должны содержать название .test || .spec и их будет запускать. Разработчики Facebook. Стал самым популярным, прост в использовании.

https://jestjs.io/

https://youtu.be/IEDe8jl5efU

Основные методы: https://habr.com/ru/post/502302/

Expect: https://jestjs.io/docs/ru/expect

Пример Jest для тестирования интерфейса в React https://webformyself.com/testirovanie-prilozhenij-react-v-2019-godu/

localhost\testing\intro-unit-testing https://github.com/SpawnMetal/intro-unit-testing

Файлы с припиской .spec либо .test будут автотестироваться

`npm run test`, команду получает из `package.json` параметр "scripts" текущей папки

## NoSQL

`#NoSQL`

### MongoDB

`#MongoDB`

```
npm i mongoose
```

https://www.mongodb.com

MongoDB — документо ориентированная система управления базами данных, не требующая описания схемы таблиц. Считается одним из классических примеров NoSQL-систем, использует JSON-подобные документы и схему базы данных.

Применяется в веб-разработке, в частности, в рамках JavaScript-ориентированного стека MEAN.

Пример кода: localhost\mern-course https://github.com/SpawnMetal/mern-course

### Redis

`#Redis`

https://redis.io

https://ru.wikipedia.org/wiki/Redis

Redis (от англ. remote dictionary server) — резидентная система управления базами данных класса NoSQL с открытым исходным кодом, работающая со структурами данных типа «ключ — значение». Используется как для баз данных, так и для реализации кэшей, брокеров сообщений.

Ориентирована на достижение максимальной производительности на атомарных операциях (заявляется о приблизительно 100 тыс. SET- и GET-запросов в секунду на Linux-сервере начального уровня[5]). Написана на Си, интерфейсы доступа созданы для большинства основных языков программирования.

Используется в основном не как основная БД:

- Для кэширвоания данных с возможностью автоматического удаления
- Обмен сообщениями между сервисами

### Firebase

`#Firebase`

https://firebase.google.com/

Что такое Firebase realtime database https://youtu.be/uf_2rDv3jDs

Firebase — это платформа для разработки приложений, которая помогает создавать и развивать приложения и игры, которые нравятся пользователям. Поддерживается Google и пользуется доверием миллионов компаний по всему миру.

Облачная, документо ориентированная система управления базами данных.

Обновляет данные онлайн, например как в гугл задачах

## Принципы

`#Принципы`

### Принципы, схемы и подходы программирования

#### Соглашения JavaScript

`#Соглашения`

camelCase для переменных и методов.

PascalCase для типов и классов.

UPPER_CASE_SNAKE_CASE для констант.

Соглашения React: PascalCase используется для названий компонентов, определённых файлов, например файлов моделей.

Хуки в React: use вначале названия хука. useName

#### MVC

`#MVC`

https://ru.wikipedia.org/wiki/Model-View-Controller

https://habr.com/ru/company/ruvds/blog/333856/

https://learn.javascript.ru/classes

Model-View-Controller (MVC, «Модель-Представление-Контроллер», «Модель-Вид-Контроллер») — схема разделения данных приложения, пользовательского интерфейса и управляющей логики на три отдельных компонента: модель, представление и контроллер — таким образом, что модификация каждого компонента может осуществляться независимо[1].

Модель (Model) предоставляет данные и реагирует на команды контроллера, изменяя своё состояние[1].

Представление (View) отвечает за отображение данных модели пользователю, реагируя на изменения модели[1].

Контроллер (Controller) интерпретирует действия пользователя, оповещая модель о необходимости изменений[1].

##### Модель

`#Модель #Model`

Модель предоставляет данные и методы работы с ними: запросы в базу данных, проверка на корректность. Модель не зависит от представления (не знает как данные визуализировать) и контроллера (не имеет точек взаимодействия с пользователем) просто предоставляя доступ к данным и управлению ими.

Модель строится таким образом, чтобы отвечать на запросы, изменяя своё состояние, при этом может быть встроено уведомление «наблюдателей».

Модель, за счёт независимости от визуального представления, может иметь несколько различных представлений для одной «модели».

Модель PenguinModel отвечает за работу с данными. В клиентском JS это означает выполнение Ajax-операций. Одно из преимуществ шаблона MVC заключается в том, что всё взаимодействие с источником данных,
например — с сервером, сосредоточено в одном месте. Такой подход помогает программистам, которые не знакомы с проектом, разобраться в нём. Модель в этом шаблоне проектирования занята исключительно работой
с JSON или объектами, которые поступают с сервера.

##### Представление

`#Представление #View`

Представление отвечает за получение необходимых данных из модели и отправляет их пользователю. Представление не обрабатывает введённые данные пользователя.

Представление PenguinView взаимодействует с DOM. DOM — это API браузера, с помощью которого работают с HTML. В MVC только представление отвечает за изменения DOM.

Представление может выполнять подключение обработчиков событий пользовательского интерфейса, но обработка событий — прерогатива контроллера. Основная задача, решаемая представлением — управлять тем,
что пользователь видит на экране. В нашем проекте представление будет выполнять манипуляции с DOM, используя JavaScript.

##### Контроллер

`#Контроллер #Controller`

Контроллер обеспечивает «связь» между пользователем и системой. Контролирует и направляет данные от пользователя к системе и наоборот. Использует модель и представление для реализации необходимого действия.

Контроллер PenguinController занимается обработкой событий и служит посредником между представлением и моделью. Он выясняет, что произошло, когда пользователь выполняет некое действие
(например, щёлкает по кнопке или нажимает клавишу на клавиатуре). Логика клиентских приложений может быть реализована в контроллере. В более крупных системах, в которых нужно обрабатывать множество событий,
этот элемент можно разбить на несколько модулей. Контроллер является входной точкой для событий и единственным посредником между представлением и данными.

#### SOLID

`#SOLID`

SOLID - принцип объектно-ориентированного программирования

Аббревиатура SOLID была предложена Робертом Мартином, автором нескольких книг, широко известных в сообществе разработчиков. Эти принципы позволяют строить на базе ООП масштабируемые и сопровождаемые программные продукты с понятной бизнес-логикой.

https://github.com/SpawnMetal/solid
https://web-creator.ru/articles/solid
https://youtu.be/xq13wiqvcTc

1. Single responsibility — принцип единственной ответственности https://youtu.be/xq13wiqvcTc?t=414

- Принцип единственной обязанности / ответственности (single responsibility principle / SRP) означает, что каждый объект должен иметь одну обязанность и эта обязанность должна быть полностью инкапсулирована в класс. Все его сервисы должны быть направлены исключительно на обеспечение этой обязанности.
- Т.е. Каждый объект со своей единственной обязанностью и все сервисы этого класса её сопровождают. Это не догма, например паттерн ActiveRecord её нарушает и делает это правильно.

2. Open-closed — принцип открытости / закрытости https://youtu.be/xq13wiqvcTc?t=1183

- Принцип открытости / закрытости (open-closed principle / OCP) декларирует, что программные сущности (классы, модули, функции и т. п.) должны быть открыты для расширения, но закрыты для изменения. Это означает, что эти сущности могут менять свое поведение без изменения их исходного кода.
- Т.е. Декларирует, что программные сущности (классы, модули, функции и т. п.) должны быть открыты для расширения, но закрыты для изменения. Например, реализовывается класс по вычислению общей площади фигур и больше код не дорабатывается.

3. Liskov substitution — принцип подстановки Барбары Лисков https://youtu.be/xq13wiqvcTc?t=2140

- Принцип подстановки Барбары Лисков (Liskov substitution principle / LSP) в формулировке Роберта Мартина: «функции, которые используют базовый тип, должны иметь возможность использовать подтипы базового типа не зная об этом».
- Т.е. Наследуемый класс не должен переписывать родителя. Это не догма, так как более ресурсоёмко.

4. Interface segregation — принцип разделения интерфейса https://youtu.be/xq13wiqvcTc?t=3024

- Принцип разделения интерфейса (interface segregation principle / ISP) в формулировке Роберта Мартина: «клиенты не должны зависеть от методов, которые они не используют». Принцип разделения интерфейсов говорит о том, что слишком «толстые» интерфейсы необходимо разделять на более маленькие и специфические, чтобы клиенты маленьких интерфейсов знали только о методах, которые необходимы им в работе. В итоге, при изменении метода интерфейса не должны меняться клиенты, которые этот метод не используют.
- Т.е. Раздельный интерфейс (React). В классе должны быть только актуальные методы и без чужих.

5. Dependency inversion — принцип инверсии зависимостей https://youtu.be/xq13wiqvcTc?t=3650

- Принцип инверсии зависимостей (dependency inversion principle / DIP) — модули верхних уровней не должны зависеть от модулей нижних уровней, а оба типа модулей должны зависеть от абстракций; сами абстракции не должны зависеть от деталей, а вот детали должны зависеть от абстракций.
- Т.е. Оборачиваем классы с реализацией функционала в классы, с которыми будет происходить взаимодействие в базовом. Тем самым работаем только с вызовом базового, ничего нигде не меняя.

#### KISS

`#KISS`

KISS — Принцип программирования - делайте вещи проще

https://web-creator.ru/articles/kiss

KISS — это принцип проектирования и программирования, при котором простота системы декларируется в качестве основной цели или ценности. Есть два варианта расшифровки аббревиатуры: «keep it simple, stupid» и более корректный «keep it short and simple».

В проектировании следование принципу KISS выражается в том, что:

не имеет смысла реализовывать дополнительные функции, которые не будут использоваться вовсе или их использование крайне маловероятно, как правило, большинству пользователей достаточно базового функционала, а усложнение только вредит удобству приложения;

не стоит перегружать интерфейс теми опциями, которые не будут нужны большинству пользователей, гораздо проще предусмотреть для них отдельный «расширенный» интерфейс (или вовсе отказаться от данного функционала);

бессмысленно делать реализацию сложной бизнес-логики, которая учитывает абсолютно все возможные варианты поведения системы, пользователя и окружающей среды, — во-первых, это просто невозможно, а во-вторых, такая фанатичность заставляет собирать «звездолёт», что чаще всего иррационально с коммерческой точки зрения.

В программировании следование принципу KISS можно описать так:
не имеет смысла беспредельно увеличивать уровень абстракции, надо уметь вовремя остановиться;

бессмысленно закладывать в проект избыточные функции «про запас», которые может быть когда-нибудь кому-либо понадобятся (тут скорее правильнее подход согласно принципу YAGNI);

не стоит подключать огромную библиотеку, если вам от неё нужна лишь пара функций;

декомпозиция чего-то сложного на простые составляющие — это архитектурно верный подход (тут KISS перекликается с DRY);

абсолютная математическая точность или предельная детализация нужны не всегда — большинство систем создаются не для запуска космических шаттлов, данные можно и нужно обрабатывать с той точностью, которая достаточна для качественного решения задачи, а детализацию выдавать в нужном пользователю объёме, а не в максимально возможном объёме.

Также KISS имеет много общего c принципом разделения интерфейса из пяти принципов SOLID, сформулированных Робертом Мартином.

#### DRY

`#DRY`

DRY - Принцип программирования — don’t repeat yourself / не повторяйте себя

https://web-creator.ru/articles/dry

Следование принципу DRY приводит к модульной архитектуре приложения и к чёткому разделению ответственности за бизнес-логику между программными классами. А это — залог сопровождаемой архитектуры.

Хотя чаще не DRY приводит к модульности, а уже модульность, в свою очередь, обеспечивает принципиальную возможность соблюдения этого принципа в больших проектах.

В проектировании DRY тоже имеет место — доступ к конкретному функционалу должен быть доступен в одном месте, унифицирован и сгруппирован по какому-либо принципу, а не «разбросан» по системе в произвольных вариациях.
Этот подход пересекается с принципом единственной ответственности из пяти принципов SOLID, сформулированных Робертом Мартином.

#### YAGNI

`#YAGNI`

YAGNI - Принцип программирования — «Вам это не понадобится»

https://web-creator.ru/articles/yagni

Если упрощенно, то следование данному принципу заключается в том, что возможности, которые не описаны в требованиях к системе, просто не должны реализовываться.

Это позволяет вести разработку, руководствуясь экономическими критериями — Заказчик не должен оплачивать ненужные ему функции, а разработчики не должны тратить своё оплачиваемое время на реализацию того, что не требуется.

Основная проблема, которую решает принцип YAGNI — это устранение тяги программистов к излишней абстракции, к экспериментам «из интереса» и к реализации функционала, который сейчас не нужен, но,
по мнению разработчика, может либо вскоре понадобиться, либо просто будет полезен, хотя в реальности такого очень часто не происходит.

Принципы YAGNI и KISS очень похожи, если KISS нацелен на упрощение и полезен в плане работы с теми требованиями, которые имеют место быть,
то YAGNI более категоричен и применяется для ограждения проектов по разработке ПО от «размывания» их рамок.

Подход к реализации проектов строго по ТЗ верен с нескольких ракурсов. Заказчик не должен платить за то, что ему не надо, а продукт должен быть максимально сопровождаем и его качество не должно страдать от интеграции ненужных функций.

#### Паттерны проектирования

`#Паттерны проектирования #design #pattern`

https://habr.com/ru/company/ruvds/blog/427293

В сфере разработки программного обеспечения паттерн проектирования (design pattern) — это повторяемая архитектурная конструкция, представляющая собой решение проблемы проектирования в рамках некоторого часто возникающего контекста. Паттерны проектирования представляют собой обобщение опыта профессиональных разработчиков ПО. Паттерн проектирования можно рассматривать как некий шаблон, в соответствии с которым пишут программы.
Определения далее содержатся на примере в папке localhost/patterns https://github.com/SpawnMetal/patterns

- `Модуль (Module)`: (patterns/pattern_module.js), вызывается при создании, обращение происходит к возвращаемым свойствам и функциям объекта, у возвращаемой функции создаётся замкнутая функция
- `Открытый модуль (Revelating Module)`: (patterns/pattern_revealing_module.js), вызывается при создании, обращение происходит к возвращаемым свойствам и функциям объекта
- `Синглтон (Singleton)`: (patterns/pattern_singleton.js), одиночка, существует в единственном экземпляре. Если объект уже имеется, возвращает его же, иначе создаёт новый.
- `Фабрика (Factory)`: (patterns/pattern_factory.js), копипаст по созданию шаблонных классов в зависимости от специфики (установленного свойства) с определением значений по умолчанию, если требуется. В общем в одном, первом вызываемом классе конструктор с условием по созданию необходимого класса.
- `Декоратор (Decorator)`: (patterns/pattern_decorator.js), создаётся шаблонный класс, затем в функциях меняются значения шаблона
- `Creational Design Patterns`: паттерны для создания объектов / классов https://youtu.be/YJVj4XNASDk
  - `Constructor (Конструктор)`: (patterns/1 creational/1_constructor.js), конструктор класса за место прототипа
  - `Factory (Фабрика)`: (patterns/1 creational/2_factory.js), множество повторяющихся классов с одинаковыми свойствами
  - `Prototype (Прототип)`: (patterns/1 creational/3_prototype.js), прототип объекта, по образу и подобию которого создаётся новый и у этого нового `__proto__` будет равен объекту родителя, хотя сами объекты не будут равны
  - `Singleton (Синглтон)`: (patterns/1 creational/4_sigleton.js), вызов конструктора создаёт объект класса только один раз, затем будет возвращать ранее созданный
- `Structural Design Pattern`: создание нового функционала для существующих объектов, не затрагивая уже существующего https://youtu.be/YJVj4XNASDk
  - `Adapter (Адаптер)`: (patterns/2 structural/5_adapter.js), позволяет интегрировать функционал например старого интерфейса в новый, не ломая всё приложение
  - `Decorator (Декоратор)`: (patterns/2 structural/6_decorator.js), позволяет навесить новый функционал на существующий объект класса
  - `Facade (Фасад)`: (patterns/2 structural/7_facade.js), создание классов через if type, например как библиотека JQuery, куда подавалось что угодно в селектор $(значение). Это значение ведь не может быть ключом объекта, чтобы реализовать как у фабрики
  - `Flyweight (Флайвейт)`: (patterns/2 structural/8_flyweight.js), пресекает повторную загрузку данных, кэширует, сохраняет в памяти и т д
  - `Proxy (Прокси)`: (patterns/2 structural/9_proxy.js), избавляет веб сервер от лишних запросов на сервер, расставляет ловушки, валидацию
- `Behaviour Design Pattern`: поведенческие паттерны для налаживания коммуникации между существующими сущностями разного типа, API, версии https://youtu.be/YJVj4XNASDk
  - `Chain of Responsibility (Цепочка обязанностей)`: (patterns/3 behaviour/10_chain_of_responsebility.js), позволяет строить цепочки вызовов функций, как у JQuery $(значение).метод1.метод2.метод3
  - `Command (Комманд)`: (patterns/3 behaviour/11_command.js), вызов функций, название которых передано в качестве строки и будет записано в некий массив вызванных команд / функций
  - `Iterator (Итератор)`: (patterns/3 behaviour/12_iterator.js), необходим для получения последовательной информации
  - `Mediator (Медиатор)`: (patterns/3 behaviour/13_mediator.js), в первую очередь позволяет выстраивать плотную и тесную коммуникацию различных типов, предоставляет централизованную абстракцию, позволяющую объектам взаимодействовать через друг друга
  - `Observer (Обсервер / Наблюдатель)`: (patterns/3 behaviour/14_observer.js), объекты подписываются на изменения другого и соответствующе реагируют
  - `State (Стейт / Состояние)`: (patterns/3 behaviour/15_state.js), верхнеуровневый класс будет менять состояние относящееся к подклассам
  - `Strategy (Стратегия)`: (patterns/3 behaviour/16_strategy.js), оболочка / семейство алгоритмов, которые наследуют объекты в разные алгоритмы и интерфейсы, не изменяя их. В нём просто вызываются функции другого класса
  - `Template (Темплейт / Шаблон)`: (patterns/3 behaviour/17_template.js), определяет скелет будущего алгоритма, а дочерние реализуют конкретный функционал на основании скелета

### Процесс разработки программного обеспечения, Жизненный цикл, MVP

`#Процесс #разработки программного обеспечения #Жизненный цикл #MVP`

- https://ru.wikipedia.org/wiki/Процесс_разработки_программного_обеспечения
- https://habr.com/ru/post/458336
- https://www.edsd.ru/ru/princypy/cikl_razrabotki_po
- https://habr.com/ru/post/527376

`#MVP`: Минимально жизнеспособный продукт (англ. minimum viable product, MVP) — продукт, обладающий минимальными, но достаточными для удовлетворения первых потребителей функциями. Основная задача — получение обратной связи для формирования гипотез дальнейшего развития продукта. Сбор информации от MVP зачастую дешевле, чем разработка продукта с большим количеством функций. Это позволяет снизить затраты и риски, если продукт не заработает, например, из-за неверных предположений.

### Реактивное программирование

`#Реактивное программирование`

https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%B0%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5

Реактивное программирование — парадигма программирования, ориентированная на потоки данных и распространение изменений. Это означает, что должна существовать возможность легко выражать статические и динамические потоки данных, а также то, что нижележащая модель исполнения должна автоматически распространять изменения благодаря потоку данных.

К примеру, в императивном программировании присваивание a = b + c будет означать, что переменной a будет присвоен результат выполнения операции b + c, используя текущие (на момент вычисления) значения переменных. Позже значения переменных b и c могут быть изменены без какого-либо влияния на значение переменной a.

В реактивном же программировании значение a будет автоматически пересчитано, основываясь на новых значениях.

### SaaS

`#SaaS`

SaaS (англ. software as a service — программное обеспечение как услуга; также англ. software on demand — программное обеспечение по требованию) — одна из форм облачных вычислений, модель обслуживания, при которой подписчикам
предоставляется готовое прикладное программное обеспечение, полностью обслуживаемое провайдером. Поставщик в этой модели самостоятельно управляет приложением, предоставляя заказчикам доступ к функциям с клиентских устройств,
как правило через мобильное приложение или веб-браузер.

https://ru.wikipedia.org/wiki/Программное_обеспечение_как_услуга

https://habr.com/ru/company/uteam/blog/113980/

## Cookie

`#Cookie`
https://github.com/js-cookie/js-cookie

## IDE

`#IDE`

IDE - Интегри́рованная среда́ разрабо́тки, ИСP (англ. Integrated development environment — IDE), также единая среда разработки, ЕСР — комплекс программных средств, используемый программистами для разработки программного обеспечения (ПО).

https://ru.wikipedia.org/wiki/Интегрированная_среда_разработки

### VSCode

`#VSCode`

VSCode (Visual Studio Code) - редактор исходного кода, разработанный Microsoft для Windows, Linux и macOS. Позиционируется как «лёгкий» редактор кода для кроссплатформенной разработки веб- и облачных приложений.

Включает в себя отладчик[8], инструменты для работы с Git[9], подсветку синтаксиса, IntelliSense[10] и средства для рефакторинга.

https://code.visualstudio.com/

https://youtu.be/QeUp3CahkQw

/\*_ Описание функции _/ - описание функции появится при наведении на её ссылку

Справа снизу можно выбрать настройки табуляции. Необходимо использовать пробелы, т. к. таб на разных ОС - это разный символ, а пробел всегда один.

Zen || Дзен - интерфейс только с редактором

Word wrap - настройка переноса строк, Word Wrap Column по умолчанию 80

При открытии параметров справа сверху есть значок с названием Параметры (JSON), там все настройки выставленные вручную, можно добавлять настройки при установке например расширений

Установить Git, синхронизировать настройки VSCode и войти через Git, F1 - Publish to GitHub. Слева снизу выводится текущая ветка.

- Ctrl + Tab - навигация по списку открытых файлов
- Ctrl + P - навигация по списку файлов в проекте
- Ctrl + W - закрытие активного файла
- Ctrl + T - #Функция отобразит список функций для перехода к ней (можно в отдельном окне справа)
- Ctrl + ~ - консоль
- Ctrl + \ - открыть файл во втором окне
- Alt + Z - Перенос не влезающих строк визуально
- Alt + Стрелка - перенос строки
- Ctrl + Shift + L - на выделенном слове, найти и выделить все свлова в файле
- Ctrl + F2 - на слово нажимаешь и находит аттрибут
- Alt + Shift + I - поставит курсоры в конец выделений

#### Сниппеты VSCode

`#Сниппеты`

- F1 - snippets - js
- $0, $2-$n - туда табнется
- $1 - туда встанет курсор
- $переменная - будет выделена

#### Расширения VSCode

`#VSCodeРасширения`

- `Bracket Pair Colorizer`: подсветит скобки https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer
- `Auto Rename Tag`: автопереименование открытых / закрытых тегов https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag
- `Open in Browser`: ПКМ в редакторе - открыть в браузере https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser
- `Live Server`: автообновление в браузере https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
- `CSS Peek`: создаёт ссылки в html на css https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek
- `Import Cost`: отображает размер импортируемых файлов https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost
- `Live Share`: для совместной разработки https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare
- `ESLint`: #Линтер контроль синтаксиса https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- `Thunder Client`: для Rest API https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client
- `Database Client`: управление БД https://marketplace.visualstudio.com/items?itemName=cweijan.vscode-database-client2
- `npm-ui`: быстрый запуск команд из package.json https://marketplace.visualstudio.com/items?itemName=imbhargav5.npm-ui
- `GitHub Copilot`: Open AI https://marketplace.visualstudio.com/items?itemName=GitHub.copilot
- `vscode-graphiql-explorer`: https://marketplace.visualstudio.com/items?itemName=GabrielNordeborn.vscode-graphiql-explorer
- `GraphQL for VSCode`: https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode
- `Architecture View NestJS`: https://marketplace.visualstudio.com/items?itemName=archsense.architecture-view-nestjs
- `Prettier`

`#Prettier`

Code formatter - форматирование https://prettier.io/ https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

Документация по параметрам: https://prettier.io/docs/en/options.html

Гугл стандарты по формату: https://google.github.io/styleguide/jsguide.html

Для активации Prettier необходимо в параметрах VSCode выставить Default Formatter и Format On Save

`.prettierrc`: конфиг

```JSON
{
  "semi": false,
  "singleQuote": true,
  "bracketSpacing": false,
  "arrowParens": "avoid",
  "printWidth": 200,
  "tabWidth": 2,
  "trailingComma": "all"
}
```

`.prettierignore`: указываются файлы для игнора

Конфиг VSCode %AppData%\Code\User\settings.json

```JSON
"[javascript]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
},
"editor.formatOnSave": true
```

- `semi`: точка с запятой, не нужна, устаревшая практика! Есть исключительные ситуации, например перед IIFE (Immediately Invoked Functional Expression, немедленно вызываемое функциональное выражение), где Prettier знает о них и ставит, иначе возникнет ошибка в коде. Гугл с этим не согласны, хотя примеров и аргументов нет https://google.github.io/styleguide/jsguide.html#formatting-semicolons-are-required
  На своей практике реализовал проект на next.js, скрипт в других проектах использую без точек с запятой, ошибок нет.
  Популярный блогер Владилен Минин их так же не использует.

- `singleQuote`: одинарные кавычки. https://google.github.io/styleguide/jsguide.html#features-strings-use-single-quotes

- `bracketSpacing`: пробелы в теле объекта { a: 1 }, не ставить. https://google.github.io/styleguide/jsguide.html#formatting-horizontal-whitespace

- `arrowParens`: скобки вокруг оператора стрелочной функции: (a) => x, не обязательны, но не промаргать их добавление при добавлении аргумента (см. совет) https://google.github.io/styleguide/jsguide.html#features-functions-arrow-functions

- `printWidth`: количество символов в строке, 200. Стандарт пока не найден.

- `tabWidth`: количество пробелов в табуляции - 2. Два пробела. Почему не символ табов? Потому что это разный символ на разных ОС и табуляция поедет, а пробелы - это единый символ. Поэтому useTabs нельзя устанавливать в true. https://google.github.io/styleguide/jsguide.html#formatting-block-indentation

- `trailingComma`: запятые в конце, ставить. https://google.github.io/styleguide/jsguide.html#features-arrays-trailing-comma

- `EditorConfig for VS Code`: импорт / экспорт настроек проекта для разных IDE https://editorconfig.org/ https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig

Предустановленные:

- `Emmet`: позволяет писать конструкции в стиле ul>li\*5 либо fs5 - font-size: 5px; При вводе ищет по введённым буквам, ! - создаёт базовый текст в html

- `npm`: пакетный менеджер, если не установлен https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script

- `JavaScript Debugger`: встроенный дебаггер https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug

### WebStorm

`#WebStorm`

https://ru.wikipedia.org/wiki/WebStorm

JetBrains WebStorm — интегрированная среда разработки на JavaScript, CSS & HTML от компании JetBrains, разработанная на основе платформы IntelliJ IDEA.

## Генератор документации

Генератор документации — программа или пакет программ, позволяющая получать документацию, предназначенную для программистов (документация на API) и/или для конечных пользователей системы,
по особым образом комментированному исходному коду и, в некоторых случаях, по исполняемым модулям (полученным на выходе компилятора).

https://ru.wikipedia.org/wiki/Генератор_документации

## Облачные сервисы

`#Облачные сервисы`

AWS (Amazon Web Services)

Azure (Microsoft Azure)

Google Cloud (Google Cloud Platform)

## API

### REST, Open API

`#REST #Open #API`

https://boodet.online/blog/rest-api-chto-eto-prostymi-slovami-principy-standarty-opisanie

REST - (от англ. Representational State Transfer — «передача состояния представления») — архитектурный стиль взаимодействия компонентов распределённого приложения в сети.

Позволяет общаться с удалёным API.

https://ru.wikipedia.org/wiki/REST

RESTful API — это интерфейс, используемые двумя компьютерными системами для безопасного обмена информацией через Интернет.

Representational State Transfer (передача состояния представления) — это программная архитектура, которая определяет условия работы API.

Веб-службы, реализующие архитектуру REST, называются веб-службами RESTful. Как правило, термин RESTful API относится к сетевым RESTful API. Однако REST API и RESTful API являются взаимозаменяемыми терминами.

Application Programming Interface (API). Интерфейс прикладного программирования определяет правила, которым необходимо следовать для связи с другими программными системами.

API Conventions (Соглашения) https://github.com/kubernetes/community/blob/master/contributors/devel/sig-architecture/api-conventions.md

`#SOAP` стоит отнести к предкам интерфейсов по типу REST API

SOAP — это протокол, который работает по заранее определенному стандарту. Ему для работы требуется XML, это определит формат, в котором будут отражаться входящие и исходящие запросы.
Основная проблема этой системы в том, что формат, который используется для передачи, излишне тяжелый.

`OpenAPI` - формализованная спецификация и экосистема множества инструментов, предоставляющая интерфейс между front-end системами, кодом библиотек низкого уровня и коммерческими решениями в виде API. Вместе с тем, cпецификация построена таким образом, что не зависит от языков программирования, и удобна в использовании как человеком, так и машиной[2].
https://ru.wikipedia.org/wiki/OpenAPI_(спецификация)

Использовать [HTTP](#HTTP):

- Get для получения
- Post для создания
- Put для обновления
- Delete для удаления
- Patch для создания либо обновления

Каждая ссылка на уникальный ресурс должна отличаться, а не быть в query, например не page=10, а использовать page/10 https://habr.com/ru/post/50147

### Swagger

`#Swagger`

https://en.wikipedia.org/wiki/Swagger_(software)

https://swagger.io/

https://youtu.be/hPzorok-gI4

Swagger — это набор инструментов для разработчиков API от SmartBear Software [1] и бывшая спецификация, на которой основана спецификация OpenAPI

## HTML

`#HTML`

https://developer.mozilla.org/en-US/docs/Web/HTML

https://developer.mozilla.org/ru/docs/Learn/HTML

HyperText Markup Language - язык гипертекстовой разметки

Спецификация https://html.spec.whatwg.org/

Тег style пишется в head. Блокирует рендер страницы http://htmlbook.ru/html/style

Тег script пишется в head либо body. Блокирует загрузку страницы до завершения скрипта, если без параметров async или defer (в случае, если порядок загрузки скриптов важен) https://developer.mozilla.org/ru/docs/Web/Performance/How_browsers_work

## CSS

`#CSS`

https://developer.mozilla.org/en-US/docs/Web/CSS
https://developer.mozilla.org/ru/docs/Learn/CSS

Cascading Style Sheets - каскадные таблицы стилей

Последний заданный стиль перебивает предыдущие, у id приоритет над классами

CSSOM дерево включает в себя стили пользовательского агента - это стили, которые браузер вставляет по умолчанию.

В CSS мы, говоря упрощённо, имеем два типа элементов — блочные и строчные. https://developer.mozilla.org/ru/docs/Learn/CSS/Building_blocks/The_box_model

Блочная вёрстка https://metanit.com/web/html5/8.1.php

`::before` https://developer.mozilla.org/en-US/docs/Web/CSS/::before

В CSS ::before создает псевдоэлемент, который является `первым` дочерним элементом выбранного элемента. Он часто используется для добавления косметического содержимого к элементу со свойством content. Он встроен по умолчанию.

`::after` https://developer.mozilla.org/en-US/docs/Web/CSS/::after

В CSS ::after создает псевдоэлемент, который является `последним` дочерним элементом выбранного элемента. Он часто используется для добавления косметического содержимого к элементу со свойством content. Он встроен по умолчанию.

`:hover` https://developer.mozilla.org/en-US/docs/Web/CSS/:hover

Псевдокласс CSS соответствует, когда пользователь взаимодействует с элементом с помощью указывающего устройства, но не обязательно активирует его. Обычно он срабатывает, когда пользователь наводит курсор на элемент (указатель мыши).

Единицы измерения https://learn.javascript.ru/css-units

position https://developer.mozilla.org/en-US/docs/Web/CSS/position

### Селекторы

`#Селекторы`

https://developer.mozilla.org/ru/docs/Web/CSS/CSS_Selectors

https://developer.mozilla.org/ru/docs/Web/CSS/Specificity#selector_types

- Универсальный - `*`
- Селектор тегов - `tag`
- Селектор классов - `.class`
- Селектор идентификаторов - `#id`
- Селектор атрибутов
  - `[attr]`
    Представляет элементы с именем атрибута attr.
  - `[attr=value]`
    Представляет элементы с именем атрибута attr, значение которого в точности равно значению .
  - `[attr~=value]`
    Представляет элементы с именем атрибута attr, значение которого представляет собой список слов, разделенных пробелами, одно из которых является точным значением .
  - `[attr|=value]`
    Представляет элементы с именем атрибута attr, значение которого может быть точно значением или может начинаться со значения, сразу за которым следует дефис -(U + 002D). Он часто используется для сопоставления языковых субкодов.
  - `[attr^=value]`
    Представляет элементы с именем атрибута attr, значение которого предваряется (предваряется) значением .
  - `[attr$=value]`
    Представляет элементы с именем атрибута attr, значение которого имеет суффикс (за которым следует) value .
  - `[attr*=value]`
    Представляет элементы с именем атрибута attr, значение которого содержит по крайней мере одно вхождение значения в строке.
  - `[attr operator value i]`
    Добавление i(или I) перед закрывающей скобкой приводит к тому, что значение сравнивается без учета регистра (для символов в диапазоне ASCII).
  - `[attr operator value s]`
    Добавление s(или S) перед закрывающей скобкой приводит к тому, что значение сравнивается с учетом регистра (для символов в диапазоне ASCII).
- Селектор потомков (контекстный селектор) - `div#paragraph1 p.note`
- Селектор дочерних элементов - `p.note > b`
- Селектор элементов одного уровня - `h1 + p`
- Селектор псевдоклассов - `a:active`
- Селектор псевдоэлементов - `p::first-letter`
- Комбинатор всех соседних элементов - `p ~ span` выберет все элементы `<span>`, которые находятся после элемента `<p>` внутри одного родителя.
- Комбинатор запятая - div, span выберет оба элемента - и `<div>` и `<span>`
- Комбинатор потомков - div span выберет все элементы `<span>`, которые находятся внутри элемента `<div>`.

### Веса CSS

`#Вес #Специфичность #Specificity`

https://developer.mozilla.org/ru/docs/Web/CSS/Specificity

В следующем списке типы селекторов расположены по возрастанию специфичности:

- селекторы типов элементов (например, `h1`) и псевдоэлементов (например, `::before`).
- селекторы классов (например, `.example`), селекторы атрибутов (например, `[type="radio"]`) и псевдоклассов (например, `:hover`).
- селекторы идентификаторов (например, `#example`).

Универсальный селектор `*`, комбинаторы `+, >, ~, ' '` и отрицающий псевдокласс `:not()` не влияют на специфичность. (Однако селекторы, объявленные внутри `:not()`, влияют)

Стили, объявленные в элементе (например, `style="font-weight:bold"`), всегда переопределяют любые правила из внешних файлов стилей и, таким образом, их специфичность можно считать наивысшей.

Важное исключение из правил - `!important`

Когда при объявлении стиля используется модификатор `!important`, это объявление получает наивысший приоритет среди всех прочих объявлений. Хотя технически модификатор `!important` не имеет со специфичностью ничего общего, он непосредственно на неё влияет.

Поскольку `!important` усложняет отладку, нарушая естественное каскадирование ваших стилей, он не приветствуется и следует избегать его использования. Если к элементу применимы два взаимоисключающих стиля с модификатором `!important`, то применён будет стиль с большей специфичностью.

### Свойства

[Flex](#Flex): положение дочерних элементов

`overflow-wrap`: предотвращение переполнения строкового поля текстом, например можно для <p> применить `overflow-wrap: anywhere`

### Flex

`#flex`

`flex` устанавливается родителю для управления положением дочерних элементов.

Игра для изучения flexbox https://flexboxfroggy.com/#ru

1. `justify-content` - горизонтальное выравнивание https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content

- `start, flex-start`: элементы выравниваются по левой стороне контейнера.
- `end, flex-end`: элементы выравниваются по правой стороне контейнера.
- `center`: элементы выравниваются по центру контейнера.
- `space-between`: элементы отображаются с одинаковыми отступами между ними.
- `space-around`: элементы отображаются с одинаковыми отступами вокруг них.

2. `align-items` - вертикальное выравнивание https://developer.mozilla.org/en-US/docs/Web/CSS/align-items

- `start, flex-start`: элементы выравниваются по верхнему краю контейнера.
- `end, flex-end`: элементы выравниваются по нижнему краю контейнера.
- `center`: элементы выравниваются вертикально по центру контейнера.
- `baseline`: элементы отображаются на базовой линии контейнера. Эта воображаемая линия проходит по нижней части букв.
- `stretch`: элементы растягиваются, чтобы заполнить контейнер.

3. `flex-direction` - направление, в котором будут расположены элементы в контейнере https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction

- `row:` элементы размещаются по направлению текста.
- `row-reverse`: элементы отображаются в обратном порядке к направлению текста.
- `column`: элементы располагаются сверху вниз.
- `column-reverse`: элементы располагаются снизу вверх.

4. `order` - порядок элементов, мо умолчанию 0, может быть отрицательным https://developer.mozilla.org/en-US/docs/Web/CSS/order
5. `align-self` - то же, что и align-items, применяется для дочерних элементов, чтобы установить расположение конкретного элемента https://developer.mozilla.org/en-US/docs/Web/CSS/align-self
6. `flex-wrap` - установка по рядам https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap

- `nowrap`: размеры элементов устанавливаются автоматически, чтобы они поместились в один ряд.
- `wrap`: элементы автоматически переносятся на новую строку.
- `wrap-reverse`: элементы автоматически переносятся на новую строку, но строки расположены в обратном порядке.

7. `flex-flow `- принимает значение через пробел `flex-direction flex-wrap` https://developer.mozilla.org/en-US/docs/Web/CSS/flex-flow
8. `align-content` - отвечает за расстояние между рядами, в то время как `align-items` отвечает за то, как элементы в целом будут выровнены в контейнере. Когда только один ряд, `align-content` ни на что не влияет. https://developer.mozilla.org/en-US/docs/Web/CSS/align-content

- `start, flex-start`: ряды группируются в верхней части контейнера.
- `end, flex-end`: ряды группируются в нижней части контейнера.
- `center`: ряды группируются вертикально по центру контейнера.
- `space-between`: ряды отображаются с одинаковыми расстояниями между ними.
- `space-around`: ряды отображаются с одинаковыми расстояниями вокруг них.
- `stretch`: ряды растягиваются, чтобы заполнить контейнер равномерно.

### margin

`#margin`

- all
- top, bottom && right, left
- top && right, left && bottom
- top, right, bottom, left

Вертикальные margin схлопываются, горизонтальные нет

### SASS, SCSS

`#SASS #SCSS`

https://sass-scss.ru/

https://youtu.be/Mrq2ora_p0o

SASS, SCSS - препроцессор, компилирует код в css

SCSS - css подобный

SASS - в виде отступов за место фигурных скобок и без точки с запятой

### LESS

`#LESS`

https://ru.wikipedia.org/wiki/LESS_(язык_стилей)

То же, что и #SCSS, только по своему

### БЭМ

`#БЭМ`

БЭМ (Блок-Элемент-Модификатор) — методология web-разработки, а также набор интерфейсных библиотек, фреймворков и вспомогательных инструментов.
https://habr.com/ru/company/ruvds/blog/347194/

`#Блок`

Блок — это независимый интерфейсный компонент. Блок может быть простым или составным (содержать другие блоки). При создании блока нужно обеспечивать возможность его использования в любом месте web-страницы, а также повторения в том же самом месте страницы (родительском элементе). Блок должен включать в себя всю реализацию, необходимую для представления части интерфейса, которую он выражает.

Пример: `.stick-man`

`#Элемент`

Элемент — это составная часть блока. Элементы контекстно-зависимы: они имеют смысл только в рамках своего блока. Элемент — не обязательная составляющая блока, небольшие блоки обходятся без элементов.

Пример: `.stick-man__head`

`#Модификатор`

Модификатор — это свойство блока или элемента, задающее изменения в их внешнем виде или поведении. Модификатор может быть булевым (например, button_big) или парой ключ-значение (например, menu_type_bullet, menu_type_numbers). У блока или элемента может быть несколько модификаторов одновременно.

Пример: `.stick-man--red`

Цель создания БЭМ

БЭМ предлагает общую семантическую модель для всех технологий, использующихся во фронтэнд разработке (HTML, CSS, JavaScript, шаблоны и др.)

Используя понятия «блок», «элемент» и «модификатор» можно описать древовидную структуру документа. Такое описание называется BEM tree и является семантическим представлением интерфейса, абстракцией над DOM tree.

## Шрифты

`#Fonts #Шрифты`

#Google https://fonts.google.com

## Typescript

`#Typescript #TS`

https://youtu.be/nyIpDs2DJ_c

TypeScript — это строго типизированный язык программирования, основанный на JavaScript. Средство разработки веб-приложений, расширяющее возможности JavaScript. Компилятор TypeScript называется tsc. Код компилируется в JavaScript. От разраба C#.

Концентрируется на добавлении «строгой типизации» для упрощения разработки и поддержки больших и сложных систем. Разработан Microsoft.

`tsconfig` https://www.typescriptlang.org/tsconfig

---

TS Playground https://www.typescriptlang.org/play

---

Utility Types (утилиты для работы с типами) https://www.typescriptlang.org/docs/handbook/utility-types.html

`Record<Keys, Type>` - Создает тип объекта, ключи свойств которого — Keysи значения свойств — Type. Эту утилиту можно использовать для сопоставления свойств одного типа с другим типом. https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type

`Record` — более предпочтителен при описании объектных типов в TypeScript. Это позволяет гибко и лаконично описывать динамические структуры и использовать Record совместно с другими типами данных.

---

SyntheticEvent - тип event у некоторых событий, описанных тут https://legacy.reactjs.org/docs/events.html#event-pooling

---

В конфиге выставить "strict": true https://medium.com/webhint/going-strict-with-typescript-be3f3f7e3295
"noImplicitAny": true - выдавать ошибку везде, где тип не указан и используется any https://www.typescriptlang.org/tsconfig#noImplicitAny
"strictNullChecks": true - для проверки null и undefined https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#null-and-undefined https://www.typescriptlang.org/tsconfig#strictNullChecks

---

Type Guards - это очевидное обычное написание кода, при использовании которого, метода может не быть, так как тип может быть number | string. Линтер подсветит такое место, а данные понятия как type guards уже слишком банальны. К ним же относятся очевидный typeof и instanceof https://www.dev-notes.ru/articles/typescript/how-to-use-type-guards-typescript/#:~:text=Защита%20типа%20—%20техника%20TypeScript%2C%20используемая,до%20чего-то%20более%20конкретного

---

Перегрузки функций https://www.typescriptlang.org/docs/handbook/2/functions.html#function-overloads

---

Можно указать, что у массива всегда только два значения https://www.typescriptlang.org/docs/handbook/2/functions.html#rest-parameters

```ts
const args = [8, 5] as const
```

---

Неизменный массив с помощью `ReadonlyArray<Type>` - то же, что и Type[]. В принципе можно использовать readonly - const todo: Readonly<Todo> либо type Foo = {readonly bas: number} https://www.typescriptlang.org/docs/handbook/utility-types.html

`readonly` - используется для свойств объектов, в классе присвоение может производиться только в конструторе https://www.typescriptlang.org/docs/handbook/2/objects.html#readonly-properties

---

Сигнатуры индекса https://www.typescriptlang.org/docs/handbook/2/objects.html#index-signatures

Тип кортежа (Tuple Types) — это еще один тип Array типа, который точно знает, сколько элементов он содержит и какие именно типы он содержит в определенных позициях https://www.typescriptlang.org/docs/handbook/2/objects.html#tuple-types

```ts
type StringNumberPair = [string, number]
```

---

- Различия между псевдонимами типов и интерфейсами https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#differences-between-type-aliases-and-interfaces
- Расширение типов происходит посредством &, а интерфейсов посредством extends
- Изменение типов невозможно в отличае от интерфейсов
- extends от примитивов у интерфейсов невозможен
- Имена интерфейсов всегда будут отображаться в сообщениях об ошибках в исходной форме, но только тогда, когда они используются по имени

---

`.!` - Оператор ненулевого утверждения (Postfix !). Необходим для утверждения, что значение не nullable, например x!.toFixed() https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#non-null-assertion-operator-postfix-

`|` - объединения. Например number | string, оба типа будут допускаться, но при использовании метода относящегося к конкретному типу сначала необходимо сделать проверку на тип https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#working-with-union-types

`&` - расширение типа. Пример:

```ts
type Animal = {
  name: string
}

type Bear = Animal & {
  honey: boolean
}

const bear = getBear()
bear.name
bear.honey
```

---

Тип утверждения https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#type-assertions

Если тип не известен и getElementById вернёт какой-то HTMLElement, можно уточнить, что это будет именно HTMLCanvasElement, в tsx за место <> использовать as

```ts
const myCanvas = document.getElementById('main_canvas') as HTMLCanvasElement
const myCanvas = <HTMLCanvasElement>document.getElementById('main_canvas')
```

---

Сигнатура вызова https://www.typescriptlang.org/docs/handbook/2/functions.html#call-signatures

```ts
type DescribableFunction = {
  description: string // Свойство
  fn: () => void // Свойство
  (someArg: number): boolean // Текущая функция
  new (s: string): Date // Можно комбинировать и вызвать текущую функцию с помощью new
}
```

---

Индексированные типы доступа https://www.typescriptlang.org/docs/handbook/2/indexed-access-types.html

```ts
const MyArray = [
  {name: 'Alice', age: 15},
  {name: 'Bob', age: 23},
  {name: 'Eve', age: 38},
]

type Person = (typeof MyArray)[number]
// type Person = {
//   name: string
//   age: number
// }

type Age = (typeof MyArray)[number]['age']
// type Age = number

// Or
type Age2 = Person['age']
// type Age2 = number
```

---

Условные типы https://www.typescriptlang.org/docs/handbook/2/conditional-types.html

```ts
SomeType extends OtherType ? TrueType : FalseType;
```

---

`infer` - создание переменной универсального типа https://www.typescriptlang.org/docs/handbook/2/conditional-types.html#inferring-within-conditional-types

```ts
type Flatten<Type> = Type extends Array<infer Item> ? Item : Type
```

---

Сопоставленные типы и модификаторы https://www.typescriptlang.org/docs/handbook/2/mapped-types.html

---

Типы шаблонных литералов https://www.typescriptlang.org/docs/handbook/2/template-literal-types.html

---

Другие типы, о которых нужно знать: `void, object, unknown, never, Function` https://www.typescriptlang.org/docs/handbook/2/functions.html#other-types-to-know-about

- `void` - когда функция возвращает просто return
- `object` - не примитивный тип
- `unknown` - например middleware, не ясно, вернёт объект с результатом или ошибку
- `never` - например, когда функция завершится за счёт вызова throw
- `Function` - функция

- `Uppercase<StringType>` - Перевести в верхний регистр https://www.typescriptlang.org/docs/handbook/2/template-literal-types.html#uppercasestringtype
- `Lowercase<StringType>` - Перевести в нижний регистр https://www.typescriptlang.org/docs/handbook/2/template-literal-types.html#lowercasestringtype
- `Capitalize<StringType>` - сделать первый символ заглавным https://www.typescriptlang.org/docs/handbook/2/template-literal-types.html#capitalizestringtype
- `Uncapitalize<StringType>` - сделать первый символ маленьким https://www.typescriptlang.org/docs/handbook/2/template-literal-types.html#uncapitalizestringtype

---

Модули `import, export` https://www.typescriptlang.org/docs/handbook/2/modules.html

---

Пространства имён `namespaces` https://www.typescriptlang.org/docs/handbook/namespaces.html

---

Декларации `declare` https://www.typescriptlang.org/docs/handbook/declaration-files/by-example.html#objects-with-properties

---

Декораторы (Decorators) https://www.typescriptlang.org/docs/handbook/decorators.html

---

Миксины - используются для расширения класса (extends) https://www.typescriptlang.org/docs/handbook/mixins.html

---

Директивы с тройной косой чертой `///` https://www.typescriptlang.org/docs/handbook/triple-slash-directives.html

### Generics

`#Generics #Генерики`

`!:` - утверждает, что присвоение значения будет осуществлено позже https://www.typescriptlang.org/docs/handbook/2/generics.html

```ts
const foo: Array<number> = [1, 2, 3] // Array - класс / объект, состоящий из number
function f<T>(array: T[]): T[]
f([1, 2]) либо f(['a', 'b']) // Подставит тип переданных значений за место T
```

Можно ограничить Type по наличию свойства https://www.typescriptlang.org/docs/handbook/2/functions.html#constraints

### enum

`#enum`

https://myrusakov.ru/js-enum-type.html

Тип enum или по-другому перечисление - это особый тип данных, который позволяет задавать некий список взаимосвязанных констант. Переменные этого типа могут принимать значения только из заданного в перечислении набора. Это свойство перечислений делает их удобным инструментом для реализации списка связанных значений.

В JavaScript на текущий момент нет нативной (родной) реализации перечислений. Typescript его предоставит https://www.typescriptlang.org/docs/handbook/enums.html

Значение перечисления изменить нельзя и оно Symbol

## Браузер

`#Браузер`

Как работают браузеры https://developer.mozilla.org/ru/docs/Web/Performance/How_browsers_work

Серверное программирование веб-сайтов https://developer.mozilla.org/ru/docs/Learn/Server-side

Browserstack фактически предоставляет вам полный удаленный доступ к виртуальным машинам, поэтому вы можете протестировать свой сайт в наиболее распространенных средах. https://www.browserstack.com

### Web Performance, Производительность, Рендер

`#Web #Performance #Производительность #Рендер`

Производительность в web https://developer.mozilla.org/ru/docs/Web/Performance

`Этапы рендеринга` включают в себя `построение DOM дерева`, `стилизацию`, `компоновку layout`, `отрисовку paint` и, в некоторых случаях, `композицию composition`. CSSOM и DOM деревья, созданные на предыдущем этапе комбинируются в дерево рендера, которое затем используется для расчёта положения каждого видимого элемента. После этого элементы будут отрисованы на экране. В некоторых случаях содержимое может быть вынесено на отдельные слои и совмещено (composition) - такой подход увеличивает производительность, позволяя отрисовывать содержимое экрана на графическом процессоре вместо ЦПУ. Это освобождает основной поток.

Сканер предзагрузки загружает скрипты и файлы заранее.

Ожидание получения CSS не блокирует парсинг HTML, но он блокирует JavaScript, потому что JavaScript часто используется для выборки узлов документа по CSS-селекторам.

#### Lazy loading

`#Lazy loading`

Ленивая загрузка. Откладывает загрузку ненужного на текущий момент контента.

Такой код в Network будет помечен как например 1.chunk.js с соответствующим комментарием вначале файла

#### Критические этапы рендеринга

`#Render #CRP`

Критические этапы рендеринга (Critical Rendering Path) https://developer.mozilla.org/ru/docs/Web/Performance/Critical_rendering_path

Производительность Web-приложений включает в себя запросы к серверу, получение ответов, загрузку, парсинг и выполнение скриптов, рендеринг, компоновку и отрисовку пикселей.

Загрузка веб-страницы или приложения начинается с запроса HTML. Сервер возвращает HTTP-ответ, состоящий из заголовков (headers) и тела запроса. Именно в теле запроса содержится HTML-документ. Браузер начинает парсить загружаемый HTML, преобразуя полученные байты документа в DOM-дерево. Браузер создаёт новый запрос каждый раз, когда он находит ссылки на внешние ресурсы, будь то файлы стилей, скриптов или ссылки на изображения. Некоторые запросы являются блокирующими. Это означает, что пока такие запросы выполняются - другие запросы приостанавливаются. Браузер продолжает парсить HTML и создавать DOM до тех пор, пока запрос на получение HTML не подходит к концу. После завершения парсинга DOM, браузер конструирует CSS модель. Как только эти модели сформированы, браузер строит дерево рендера (render tree), в котором вычисляет стили для каждого видимого элемента страницы. После формирования дерева происходит компоновка (layout), которая определяет положение и размеры элементов этого дерева. Как только этап завершён - страница рендерится. Или "отрисовывается" (paint) на экране.

1. Document Object Model.

Ответ в виде HTML превращается в токены, которые превращаются в узлы (nodes), которые формируют DOM дерево.

2. CSS Object Model.

CSS блокирует рендер: браузер блокирует рендеринг страницы до тех пор, пока не получит и не обработает все CSS-правила. CSS блокирует рендеринг, потому что правила могут быть перезаписаны, а значит, необходимо дождаться построения CSSOM, чтобы убедиться в отсутствии дополнительных переопределений.

CSSOM дерево включает в себя стили пользовательского агента - это стили, которые браузер вставляет по умолчанию.

3. Render Tree.

Дерево рендера охватывает только видимое содержимое. Например, секция head (в основном) не содержит никакой видимой информации, а потому может не включаться в дерево. Кроме того, если у какого-то узла стоит свойство display: none, оно так же не включается в дерево (как и потомки этого узла).

После формирования дерева происходит компоновка и отрисовка см [Этапы рендера](#Этапы-рендера)

##### Этапы рендера

`#Render #Layout #Paint #Compositing`

Происходит после формирования дерева (Render Tree). см п.3 [Критические этапы рендеринга](#Критические-этапы-рендеринга)

1. `Компоновка (Layout)` определяет размеры и позицию каждого элемента на странице. Как только компоновка определена - пиксели отрисовываются на экране. Так же возникает при изменении размеров окна в браузере.

2. `Отрисовка (Paint)`
   При первичной загрузке документа (onload) весь экран будет отрисован.
   После этого будут перерисовываться только необходимые к обновлению части экрана.
   Отрисовка может разбить элементы в дереве рендера на слои. Для того, чтобы ускорить их рендер, браузер может перенести отрисовку разных слоёв на GPU (вместо основного потока CPU) - Композиция (Compositing).
   Чтобы обеспечить плавную прокрутку и анимацию, отрисовка каждого элемента занимает весь основной поток. Сюда включается вычисление стилей, повторное вычисление стилей и отрисовка. Все эти этапы должны выполняться не дольше 16.67 мс. (1000мс. / 60 кадров в секунду).

3. `Композиция (Compositing)`
   Для переноса вычислений отрисовки на GPU вы можете использовать некоторые специальные HTML теги, например `<video>` и `<canvas>`, а также CSS-свойства opacity, transform и will-change.
   Слои улучшают производительность. Но, с точки зрения управления памяти, они неэффективны. Поэтому старайтесь не использовать их там, где в них нет необходимости.

---

- Оптимизация CRP
  Уменьшайте количество критических ресурсов, откладывая их загрузку, помечая их как async и/или группируя их;
  Оптимизируйте количество необходимых запросов, а так же размеры файлов;
  Оптимизируйте порядок так, чтобы критические ресурсы загружались в первую очередь, сокращая таким образом длину критических этапов рендеринга.

- Советы по оптимизации
  Проверьте зависимости проекта. Избавьтесь от всего ненужного.
  Разделите код на небольшие фрагменты вместо того, чтобы складывать его в один большой файл.
  Откладывайте, в тех ситуациях, когда это возможно, загрузку JS-скриптов. При обработке текущего маршрута пользователю можно выдавать только тот код, который необходим для нормальной работы, и ничего лишнего.
  Используйте инструменты разработчика и средства вроде DeviceTiming для того, чтобы находить узкие места своих проектов.
  Используйте средства вроде Optimize.js для того, чтобы помочь парсерам определиться с тем, какие фрагменты кода им нужно обработать как можно скорее.

- Интерактивность
  Time to Interactive (TTI, время до интерактивности) - это показатель того, как много времени проходит между самым первым сетевым запросом и моментом, когда страница становится интерактивной. В хронологии этот этап следует сразу за First Contentful Paint.
  Интерактивностью называется показатель того, что страница отреагировала на действие пользователя за время в 50мс.

---

`window.requestAnimationFrame(callback)` - предоставляет разработчикам доступ к жизненному циклу фрейма, позволяя выполнять операции перед вычислением стилей и формированием макета (layout) документа браузером. Вот почему данный метод отлично подходит для реализации анимации. Собственно, для этого он и предназначен. https://habr.com/ru/companies/timeweb/articles/587908/ https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame#examples

### Сеть

`#Сеть`

`#DNS` (Domain Name System или система доменных имён). DNS — это технология, которая позволяет браузеру найти запрошенный пользователем сайт по его имени https://selectel.ru/blog/dns-server/

1. Ввод адреса в браузере
2. 2 сообщения: Поиск ip введённого домена и остальных параметров на DNS сервере провайдера
3. 3 сообщения: Трёхэтапное рукопожатие TCP - это техника, очень часто упоминаемая как "SYN-SYN-ACK" (SYN, SYN-ACK, ACK, если быть точнее), т.к. при установке соединения передаются 3 сообщения. Это означает, что прежде чем установится соединение, браузер должен обменяться ещё тремя сообщениями с сервером.
4. 5 сообщений: при сертификате TLS.

Transport Layer Security (TLS) - Безопасность Транспортного Уровня (протокол), ранее известный как Secure Sockets Layer (SSL) - Уровень Защищённых Соединений используется приложениями для организации защищённой передачи данных через интернет, предотвращая взлом и прослушивание электронной почты, просмотра сайтов, переписки и прочих протоколов. https://developer.mozilla.org/ru/docs/Glossary/TLS 5. 1 сообщение: Как только мы установили соединение с веб-сервером, браузер отправляет инициирующий HTTP GET запрос от имени пользователя. Чаще всего запрашивается HTML файл. В момент, когда сервер получает запрос, он начинает ответ с посылки заголовков ответа и содержимым HTML-файла.

SSL и TLS - в чем разница? https://youtu.be/OmlkEhRHRTA?si=fdnVTqbq9s2B1LT4

Этот ответ содержит в себе первый байт полученных данных.

Первый пакет обычно содержит 14КБ данных.

Time to first byte https://developer.mozilla.org/ru/docs/Glossary/time_to_first_byte

Время до первого байта (англ. Time to First Byte, TTFB) - одна из метрик производительности веб-страниц, которая описывает время, которое прошло с момента отправления браузером запроса страницы до момента, когда он получил первый байт информации с сервера. Это время включает в себя поиск DNS-сервера и установление соединения с использованием TCP-рукопожатия и SSL-рукопожатия, если запрос выполняется через https.

URL https://developer.mozilla.org/ru/docs/Glossary/URL

Единый указатель ресурса (Uniform Resource Locator, URL) — строка, однозначно определяющая, где в интернете находится ресурс.

В контексте HTTP, URL называют "адрес" (web address)" или "ссылку" (link).

#### MTLS

`#MTLS`

https://investim.guru/news/chem-otlichayutsya-tls-i-mtls-v-chem-zaklyuchaetsya-raznitsa

Mutual TLS (MTLS)

- Взаимная аутентификация

Одно из главных отличий между TLS и MTLS заключается в том, что MTLS предоставляет возможность для взаимной аутентификации между клиентом и сервером. Это означает, что клиент и сервер должны предоставить доказательства своей подлинности друг другу, например, сертификаты X.509.

- Безопасность двухстороннего соединения

Так как MTLS предоставляет взаимную аутентификацию, он обеспечивает безопасность обоих сторон соединения. Клиент может быть уверен в том, что он соединяется с доверенным сервером, а сервер может быть уверен в идентификации клиента. Это делает MTLS особенно полезным в ситуациях, где требуется большая степень безопасности, например, в финансовых или медицинских приложениях.

- Использование сертификатов

Как TLS, так и MTLS используют сертификаты для аутентификации и шифрования данных. Однако, в случае MTLS, обе стороны соединения должны предоставить действительные сертификаты. Клиент будет использовать сертификат сервера для проверки его подлинности, а сервер будет использовать сертификат клиента для проверки его подлинности. Таким образом, MTLS обеспечивает более сильное доверие в сравнении с обычным TLS.

#### HTTP

`#HTTP`
HTTP (Hypertext Transfer Protocol - гипертекстовый транспортный протокол) https://developer.mozilla.org/ru/docs/Glossary/HTTP

Протокол передачи гипертекста (HTTP) является базовым сетевым протоколом, который позволяет передавать гипермедиа документы в Web, обычно между браузером и сервером, таким образом, что бы люди могли их читать.

HTTP является текстовым (все сообщения осуществляются в виде простого текста), без запоминания состояния (нет информации о предыдущих сообщениях).

HTTP запрос состоит из https://developer.mozilla.org/ru/docs/Web/HTTP/Messages

1. Стартовой строки: GET, POST, ...
2. Заголовков (Headers)
3. Тело (Body) опционально

HTTP ответ состоит из https://developer.mozilla.org/ru/docs/Web/HTTP/Messages

1. Строка статуса (Status line): 200, 404, ...
2. Заголовков (Headers)
3. Тело (Body) опционально

Для HTTP порт по умолчанию – 80, для HTTPS – 443

`#Коды` `#ответа` HTTP https://developer.mozilla.org/ru/docs/Web/HTTP/Status

Например, коды 2XX указывают на успешное выполнение, а коды 4XX и 5XX — на ошибки. Коды 3XX указывают на перенаправление URL.

- `200`: общий ответ об успешном выполнении
- `201`: ответ об успешном выполнении метода POST
- `400`: Bad Request "Плохой запрос". Этот ответ означает, что сервер не понимает запрос из-за неверного синтаксиса.
- `401`: Unauthorized "Неавторизованно". Для получения запрашиваемого ответа нужна аутентификация. Статус похож на статус 403, но, в этом случае, аутентификация возможна.
- `403`: Forbidden "Запрещено". У клиента нет прав доступа к содержимому, поэтому сервер отказывается дать надлежащий ответ.
- `404`: ресурс не найден

Методы https://developer.mozilla.org/ru/docs/Web/HTTP/Methods

`PUT` является `идемпотентным`, т.е. единичный и множественные вызовы этого метода, с идентичным набором данных, будут иметь тот же результат выполнения (без сторонних эффектов), в случае с POST, множественный вызов с идентичным набором данных может повлечь за собой сторонние эффекты.

A `PATCH` `не обязательно идемпотентен`, хотя может быть.

## Алгоритмы и структуры данных

`#Алгоритмы и #структуры данных`

Классические алгоритмы и структуры данных на JavaScript https://habr.com/ru/post/359192/

Алгоритмы и структуры данных https://github.com/trekhleb/javascript-algorithms/blob/master/README.ru-RU.md

Распространенные алгоритмы и структуры данных в JavaScript: основные понятия и работа с массивами https://proglib.io/p/rasprostranennye-algoritmy-i-struktury-dannyh-v-javascript-osnovnye-ponyatiya-i-rabota-s-massivami-2021-10-06

Распространенные алгоритмы и структуры данных в JavaScript: стеки, очереди и связные списки https://proglib.io/p/rasprostranennye-algoritmy-i-struktury-dannyh-v-javascript-steki-ocheredi-i-svyaznye-spiski-2021-10-13

https://developer.mozilla.org/ru/docs/Glossary/Algorithm

Алгоритм — это независимая серия инструкций для выполнения функции.

Различают `устойчивые` и `неустойчивые` алгоритмы. Первые не изменяют порядок элементов, а вторые могут его изменять.

Структура данных (англ. data structure) — программная единица, позволяющая хранить и обрабатывать множество однотипных и/или логически связанных данных в вычислительной технике. Для добавления, поиска, изменения и удаления данных структура данных предоставляет некоторый набор функций, составляющих её интерфейс.

Пояснения алгоритмической сложности https://www.bigocheatsheet.com/

Примеры

localhost\examples\map.js https://github.com/SpawnMetal/examples

Рекурсивный обход дерева localhost\examples\treerec.js https://github.com/SpawnMetal/examples

---

`#Sort #Sorting #Сортировки`

https://techrocks.ru/2020/08/08/sorting-algorithms-with-examples-in-javascript/
https://www.toptal.com/developers/sorting-algorithms
https://www.bigocheatsheet.com/

Пример localhost\sortings https://github.com/SpawnMetal/sortings

Фцнкция sort() использует сортировку вставкой (Insertion). Преобразует в строку и если условие сортировки возвращает положительное значение, тогда осуществляется перестановка, поэтому возвращаем a - b.
Если a и b равны, то вернется 0. В этом случае порядок элементов может сохраниться, а может и поменяться. Глобально это не повлияет на задачу сортировки, но может иметь различные побочные эффекты.
localeCompare() используется для сортировки строк, возвращая значение при сравнении

Самые быстрые:

- Сортировка по основанию (Radix sort) https://en.wikipedia.org/wiki/Radix_sort
- Сортировка подсчетом (Counting sort) https://en.wikipedia.org/wiki/Counting_sort

### Bubble

`#Bubble Сортировка #пузырьком`

- Сортировка пузырьком
- Алгоритм: Сравнивает два соседних значения и меняет их местами, если первое значение больше второго
- Временная сложность в наилучшем случае — O(N), в наихудшем — O(N^2)

### Selection

`#Selection Сортировка #выбором`

- Сортировка выбором
- Алгоритм: В основе сортировки выбором лежит следующий подход: мы находим минимальное значение в структуре данных и помещаем его на первую позицию, затем находим второе минимальное значение и помещаем его на вторую позицию и так далее
- Временная сложность в наилучшем и наихудшем случае — O(N^2)

### Insertion

`#Insertion Сортировка #вставками`

- Сортировка вставками
- Алгоритм сортировки вставками строит финальный отсортированный массив по одному значению за раз. Процесс выглядит следующим образом:
- Предполагаем, что первый элемент уже отсортирован.
- Сравниваем первый элемент со вторым: должно ли второе значение остаться на месте или же оно должно быть вставлено перед первым значением?
- Далее аналогичное сравнение делается для третьего значения: должно ли оно быть вставлено на первую, вторую или третью позицию? И так далее.
- Временная сложность в наилучшем случае — O(N), в наихудшем — O(N^2)

### Merge

`#Merge Сортировка #слиянием`

- Сортировка слиянием
- Алгоритм сортировки слиянием это один из алгоритмов «разделяй и властвуй»). Другими словами, он делит исходный массив на более мелкие массивы, пока каждый маленький массив не будет содержать всего одну позицию, а затем сливает маленькие массивы в более крупный и отсортированный.
- Временная сложность в наилучшем и наихудшем случае — O(N Log N)

### Quick

`#Quick #Быстрая сортировка`

- Быстрая сортировка
- Быстрая сортировка это один из наиболее часто используемых алгоритмов сортировки
- Алгоритм:
- 1. Выбираем значение в массиве, которое назовем опорным. Обычно это значение в середине массива.
- 2. Осуществляем операцию распределения, в результате которой значения меньше опорного смещаются влево от опорного, а большие — вправо от него.
- 3. Повторяем первые два шага для каждого подмассива (левого и правого), пока массивы не будут полностью отсортированы.
- Временная сложность в наилучшем случае — O(N), в наихудшем — O(N^2)

## Брокер

`#Сообщения #Брокер`

### RabbitMQ

`#RabbitMQ`

https://www.rabbitmq.com/

https://ru.wikipedia.org/wiki/RabbitMQ

RabbitMQ — программный брокер сообщений на основе стандарта AMQP — тиражируемое связующее программное обеспечение, ориентированное на обработку сообщений. Создан на основе системы Open Telecom Platform, написан на языке Erlang, в качестве движка базы данных для хранения сообщений использует Mnesia.

### NATS

`#NATS`

https://nats.io/

https://en.wikipedia.org/wiki/NATS_Messaging

NATS — это система обмена сообщениями с открытым исходным кодом (иногда называемая промежуточным программным обеспечением, ориентированным на сообщения ). Сервер NATS написан на языке программирования Go . Клиентские библиотеки для взаимодействия с сервером доступны для десятков основных языков программирования. Основными принципами проектирования NATS являются производительность, масштабируемость и простота использования. [2] Аббревиатура NATS расшифровывается как Neural Autonomic Transport System.

## Определения

`#Определения`

### SSR

`#SSR`

https://blog.vverh.digital/2020/what-is-it-ssr-chto-takoe/

SSR – (анг. аббревиатура от Server Side Rendering) это технология, которая позволяет, с помощью Node.js, запускать JavaScript код на сервере (а не в браузере как обычно) и готовый результат отправлять пользователю, избегая лишней нагрузки на его браузер и компьютер.

Зачем нужен SSR:

В первую очередь, для оптимизации скорости работы сайта и SEO продвижения.

### SEO

`#SEO`

https://ru.wikipedia.org/wiki/Поисковая_оптимизация

Поисковая оптимизация (англ. search engine optimization, SEO) — комплекс мероприятий по внутренней и внешней оптимизации для поднятия позиций сайта в результатах выдачи поисковых систем по определённым запросам пользователей, с целью увеличения сетевого трафика (для информационных ресурсов) и потенциальных клиентов (для коммерческих ресурсов) и последующей монетизации (получение дохода) этого трафика. SEO может быть ориентировано на различные виды поиска, включая поиск информации, товаров, услуг, изображений, видеороликов, новостей и специфические отраслевые поисковые системы.

### middleware

`#middleware`

[Middleware][middleware]

[Написание кода промежуточных обработчиков для использования в приложениях Express][express-middleware]

Функции промежуточной обработки (`middleware`) - это функции, имеющие доступ к объекту запроса `req`, объекту ответа `res` и к следующей функции промежуточной обработки в цикле `запрос-ответ` приложения.

Следующая функция промежуточной обработки, как правило, обозначается переменной `next`.

### Декларативное, Императивное программирование

`#Декларативное #Императивное программирование`
https://habr.com/ru/post/324688/

`Декларативное программирование` - это когда в коде описано что должно получиться, а императивное - когда написано как это сделать.

`Декларати́вное программи́рование` — это парадигма программирования, в которой задаётся спецификация решения задачи, то есть описывается, что представляет собой проблема и ожидаемый результат.

Противоположностью декларативного является императивное программирование, описывающее на том или ином уровне детализации, как решить задачу и представить результат. В общем и целом, декларативное программирование идёт от человека к машине, тогда как императивное — от машины к человеку.

Как следствие, декларативные программы не используют понятия состояния, то есть не содержат переменных и операторов присваивания (см. также ссылочная прозрачность).

### Declaration, Expression Function

`#Declaration #Expression #Function`

https://learn.javascript.ru/function-expressions

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Function

`Function Declaration` (`Объявление Функции`, можно вызвать до объявления):

```js
function sayHi() {
  alert('Привет')
}
```

`Function Expression` (`Функциональное Выражение`, нельзя вызвать до объявления):

```js
var sayHi = function () {
  alert('Привет')
}
```

`#Зона выражения`

Зоной выражения считаются: присваивание(=), операторы || или иные логические операторы, тернарный оператор, инициализатор массива, перечисление через запятую.

### Анонимная функция

`#Анонимная функция`

У них нет имён, поэтому они называются анонимными

```js
function() {return a}

() => a
```

### JSON

`#JSON`

https://ru.wikipedia.org/wiki/JSON

JSON (англ. JavaScript Object Notation) — текстовый формат обмена данными, основанный на JavaScript.

JSON сервер для тестовых запросов https://jsonplaceholder.typicode.com/

### use strict

`#use strict #Строгий режим`

https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Strict_mode

Режим strict (строгий режим), введенный в ECMAScript 5, позволяет использовать более строгий вариант JavaScript.

Строгий режим принёс ряд изменений в обычную семантику JavaScript.

- Во-первых, строгий режим заменяет исключениями некоторые ошибки, которые интерпретатор JavaScript ранее молча пропускал.
- Во-вторых, строгий режим исправляет ошибки, которые мешали движкам JavaScript выполнять оптимизацию -- в некоторых случаях код в строгом режиме может быть оптимизирован для более быстрого выполнения, чем код в обычном режиме.
- В-третьих, строгий режим запрещает использовать некоторые элементы синтаксиса, которые, вероятно, в следующих версиях ECMAScript получат особый смысл.

### Транспиляция

`#Транспайлер #Транспиляция`

Транспайлер — программа, выполняющая транспиляцию программы. Транспиляция — преобразование программы, при котором используется исходный код программы, написанной на одном языке программирования в качестве исходных данных, и производится эквивалентный исходный код на другом языке программирования.

### Нативный

`#Нативный`

Нативный - означает родной, исходный, первоначальный.

Нативные приложения (англ. native application) — это прикладные программы, которые были разработаны для использования на определённой платформе или на определённом устройстве.

### Адаптивность, Отзывчивость

`#Адаптивность #Отзывчивость`

https://html5book.ru/otzyvchivyj-dizayn-saita/

- `Адаптивный дизайн`: один макет для каждого устройства
- `Отзывчивый дизайн`: один макет для всех устройств

- `Adaptive Design (AWD)`: адаптивный дизайн, или динамический показ — проектирование сайта с условиями, которые изменяются в зависимости от устройства, базируясь на нескольких макетах фиксированной ширины.
- `Responsive Design (RWD)`: отзывчивый дизайн — проектирование сайта с определенными значениями свойств, например, гибкая сетка макета, которые позволяют одному макету работать на разных устройствах;

### Accessibility

`#Accessibility #Доступность`

https://developer.mozilla.org/ru/docs/Web/Accessibility

Доступность (Accessibility, A11y в англоязычной среде) в веб-разработке — это обеспечение возможности использования сайтов как можно большим числом людей, включая тех, чьи способности как-либо ограничены.

### Семантика

`#Semantics #Семантика`

https://developer.mozilla.org/ru/docs/Glossary/Semantics
В программировании, Семантика означает значение фрагмента кода - например, «к какому результату приведёт выполнение этой строки JavaScript?», или «каково предназначение или какая роль у этого элемента HTML» (а не «как он выглядит ?».)

### Layout

`#Layout`

Неизменная часть сайта, некий шаблон

### Legacy code

`#Legacy code`

https://en.wikipedia.org/wiki/Legacy_system

Legacy code - устаревший, но используемый код

### Миксин

`#Миксин`

https://developer.mozilla.org/ru/docs/Glossary/Mixin

Миксин (дословно: "примесь") - класс (class) или интерфейс, в котором некоторые или все его методы (methods) и/или свойства (properties) не реализованы, требуя, чтобы другой класс или интерфейс обеспечивал недостающие реализации. Новый класс или интерфейс затем включает в себя как свойства и методы из миксина, так и те, которые он определяет сам. Все методы и свойства используются совершенно одинаково, независимо от того, реализованы ли они в миксине, интерфейсе или классе, реализующем миксин.

Преимущество миксинов заключается в том, что они могут быть использованы для упрощения проектирования API, в которых несколько интерфейсов должны включать одни и те же методы и свойства.

Например, миксин WindowOrWorkerGlobalScope используется для предоставления методов и свойств, которые должны быть доступны как в интерфейсах Window, так и в интерфейсах WorkerGlobalScope. Миксин осуществляется с помощью обоих этих интерфейсов.

### Палиндром

`#Палиндром`

Текст, который читается одинаково в обоих направлениях, например довод.

`split` строку, `reverse` массив, `join` обратно в строку

### Сборка мусора

`#Сборка #мусора #Управление #памятью`

https://learn.javascript.ru/memory-management
https://learn.javascript.ru/garbage-collection
https://developer.mozilla.org/ru/docs/Web/JavaScript/Memory_Management

Более низкоуровневое объяснение https://jayconrod.com/posts/55/a-tour-of-v8-garbage-collection

Основной концепцией управления памятью в JavaScript является принцип достижимости. Если упростить, то «достижимые» значения – это те, которые доступны или используются. Они гарантированно находятся в памяти.

Большая часть алгоритмов сборки мусора основана на понятии ссылки. В контексте управления памятью объект считается ссылающимся на другой объект, если у первого есть доступ ко второму (неважно - явный или неявный). К примеру, каждый объект JavaScript имеет ссылку на свой прототип (неявная ссылка) и ссылки на значения своих полей (явные ссылки).

`Недостижимый «остров»`: Вполне возможна ситуация, при которой целый «остров» взаимосвязанных объектов может стать недостижимым и удалиться из памяти.

1. Сборка мусора на основе подсчёта ссылок

Это наиболее примитивный алгоритм сборки мусора, сужающий понятие "объект более не нужен" до "для данного объекта более нет ни одного объекта, ссылающегося на него". Объект считается подлежащим уничтожению сборщиком мусора, если количество ссылок на него равно нулю.

Основное ограничение данного наивного алгоритма заключается в том, что если два объекта ссылаются друг на друга (создавая таким образом циклическую ссылку), они не могут быть уничтожены сборщиком мусора, даже если "более не нужны".

2. Алгоритм "Mark-and-sweep"

Данный алгоритм сужает понятие "объект более не нужен" до "объект недоступен".

Основывается на понятии о наборе объектов, называемых roots (в JavaScript root'ом является глобальный объект). Сборщик мусора периодически запускается из этих roots, сначала находя все объекты, на которые есть ссылки из roots, затем все объекты, на которые есть ссылки из найденных и так далее. Стартуя из roots, сборщик мусора, таким образом, находит все доступные объекты и уничтожает недоступные.

Данный алгоритм лучше предыдущего, поскольку "ноль ссылок на объект" всегда входит в понятие "объект недоступен". Обратное же - неверно, как мы только что видели выше на примере циклических ссылок.

Начиная с 2012 года, все современные веб-браузеры оснащаются сборщиками мусора, работающими исключительно по принципу mark-and-sweep ("пометь и выброси"). Все усовершенствования в области сборки мусора в интерпретаторах JavaScript (генеалогическая/инкрементальная/конкурентная/параллельная сборка мусора) за последние несколько лет представляют собой усовершенствования данного алгоритма, но не новые алгоритмы сборки мусора, поскольку дальнейшее сужение понятия "объект более не нужен" не представляется возможным.

Поэтому объекты ссылающиеся друг на друга, но недоступные из ГО будут удалены.

Так же интерпретиторы оптимизируют сборку и удаляют замкнутые переменные, если они более недоступны и не используются функцией, в Scope которой можно было использовать верхнеуровневую переменную.

### Веб-безопасность

`#Веб-безопасность #безопасность`

https://developer.mozilla.org/ru/docs/Learn/Server-side/First_steps/Website_security

### Полифил

`#Полифил #Polyfill`

https://developer.mozilla.org/ru/docs/Glossary/Polyfill

Полифил — это фрагмент кода (в сети — обычно JavaScript), который позволяет использовать современную функциональность в более старых браузерах, которые не поддерживают ее по умолчанию.

### Микросервис

`#Микросервис #Microservices`

https://martinfowler.com/articles/microservices.html

В Nest микросервис — это, по сути, приложение, использующее транспортный уровень, отличный от HTTP.

Один разработчик должен тратить на его разработку недели две, иначе он станет сложным

Принципы

- `loosley coupled`: слабосвязанные. Сервисы могут ничего не знать друг о друге, но могут вызывать друг друга при необходимости
- `small`: небольшой функционал, отделённый от других по смыслу: работа с юзерами, заказ билетов и т д
- `cloud`: микросервис не должен быть сам по себе, он должен быть в неком облаке / пространстве с остальными
- `decentralized`: каждый микросервис разрабатывается и обновляется независимо от остальных

Микросервисы могут отдельно разрабатываться и быть на разных языках

Паттерны

- API Gateway
- Межсервисная коммуникация
- Service Discovery
- CQRS (Command–query separation)
- Event sourcing

Что есть в микросервисной архитектуре?

- `Gateway`: Главный сервер, который принимает запросы и перенаправляет их нужному микросервису. Чаще всего, в gateway нет никакой бизнес-логики.
- `Microservice`: Сам микросервис, который обрабатывают запросы пользователей с четко заданной бизнес-логикой.
- `Транспорт`: Это та часть, через которую будут общаться Gateway & Microservice. В качестве транспорта могут выступать HTTP, gRPC, RabbitMQ и т.д.

https://docs.nestjs.com/microservices/basics

На примере NestJS + Kafka https://youtu.be/7-dgkxLgbBM

### Developer vs Engineer vs Architect

`#Developer #Engineer #Architect`

https://habr.com/ru/post/135865

### CI CD

`#CI #CD`

см [Инструменты CI CD](#Инструменты-CI-CD)

https://habr.com/ru/company/otus/blog/515078/

Непрерывная интеграция (Continuous Integration, CI) и непрерывная поставка (Continuous Delivery, CD) представляют собой культуру, набор принципов и практик, которые позволяют разработчикам чаще и надежнее развертывать изменения программного обеспечения.

CI/CD — это одна из DevOps-практик. Она также относится и к agile-практикам: автоматизация развертывания позволяет разработчикам сосредоточиться на реализации бизнес-требований, на качестве кода и безопасности.

### UX UI

`#UX #UI`

https://habr.com/ru/post/321312/

UX — это User Experience (дословно: «опыт пользователя»). То есть это то, какой опыт/впечатление получает пользователь от работы с вашим интерфейсом. Удается ли ему достичь цели и на сколько просто или сложно это сделать.

UI — это User Interface (дословно «пользовательский интерфейс») — то, как выглядит интерфейс и то, какие физические характеристики приобретает. Определяет, какого цвета будет ваше «изделие», удобно ли будет человеку попадать пальцем в кнопочки, читабельным ли будет текст и тому подобное…

UX/UI дизайн — это проектирование любых пользовательских интерфейсов в которых удобство использования так же важно как и внешний вид.

### Артефакт, билд

`#Artefact #Артефакт #Билд #Build`

Скомпилированный код

### Деплой

`#Deploy`

Скопированный проект

[middleware]: https://developer.mozilla.org/en-US/docs/Glossary/Middleware
[express-middleware]: https://expressjs.com/ru/guide/writing-middleware.html#:~:text=%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8%20%D0%BF%D1%80%D0%BE%D0%BC%D0%B5%D0%B6%D1%83%D1%82%D0%BE%D1%87%D0%BD%D0%BE%D0%B9%20%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8%20(middleware)%20%2D,%D0%BA%D0%B0%D0%BA%20%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%BE%2C%20%D0%BE%D0%B1%D0%BE%D0%B7%D0%BD%D0%B0%D1%87%D0%B0%D0%B5%D1%82%D1%81%D1%8F%20%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20next%20
[linked-list]: https://itchef.ru/articles/125551/#:~:text=%D0%A1%D0%B2%D1%8F%D0%B7%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9%20%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA%20%E2%80%94%20%D1%8D%D1%82%D0%BE%20%D1%82%D0%B8%D0%BF%20%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D1%8B,%D0%B5%D1%81%D1%82%D1%8C%20%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%20%D0%BD%D0%B0%20%D0%BF%D1%80%D0%B5%D0%B4%D1%8B%D0%B4%D1%83%D1%89%D0%B8%D0%B9%20%D1%83%D0%B7%D0%B5%D0%BB

### Tree shaking

`#TreeShaking #Тришейкинг`

Это удаление лишнего кода и импортов, осуществляется бандлерами (сборщиками).

В esbuild `treeShaking : true` https://esbuild.github.io/api/#tree-shaking

В Webpack `mode: "production"` https://webpack.js.org/guides/tree-shaking/
