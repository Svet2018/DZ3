## GitHub - крупнейший веб-сервис для хостинга IT-проектов и их совместной разработки.

Веб-сервис основан на системе контроля версий Git и разработан на Ruby on Rails и Erlang компанией GitHub, Inc (ранее Logical Awesome). 

Создатели сайта называют GitHub «социальной сетью для разработчиков».

Кроме размещения кода, участники могут общаться, комментировать правки друг друга, а также следить за новостями знакомых.

С помощью широких возможностей Git программисты могут объединять свои репозитории — GitHub предлагает удобный интерфейс для этого и может отображать вклад каждого участника в виде дерева. 

Главной целью этого сервиса является поддержка совместной разработки проектов и контроля версий.

## Работа с удаленным репозиторием

Для загрузки данных в удаленный репозитарию сначала нужно к нему подключиться.

1. Регистрация на GitHub
2. GitHub позволяет работать с репозиториями тремя способами: SSH, HTTP и Git Read-Only, соответственно предоставляя ссылки трех видов для нашего репозитория:
#### git@github.com:habrauser/Hello-world.git
#### habrauser@github.com/habrauser/Hello-world.git
#### git://github.com/habrauser/Hello-world.git

3. Синхронизация с удалённым репозиторием

*Регистрация удалённого репозитория и обмен изменениями*

* $ git fetch [удалённый репозиторий]

*Скачивает всю историю из удалённого репозитория*

* $ git merge [удалённый репозиторий]/[ветка]

*Вносит изменения из ветки удалённого репозитория в текущую ветку локального репозитория*

* $ git push [удалённый репозиторий] [ветка]

*Загружает все изменения локальной ветки в удалённый репозиторий*

* $ git pull

*Загружает историю из удалённого репозитория и объединяет её с локальной*

* pull = fetch + merge


**Git и GitHub**

Git — это инструмент, позволяющий реализовать распределённую систему контроля версий, а GitHub — это сервис для проектов, использующих Git.