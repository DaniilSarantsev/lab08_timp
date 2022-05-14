----
## Работа с Docker
----
docker run ubuntu echo 'hello from ubuntu'
----

Сборка и настройка собственного образа и контейнера Docker:
----
docker build -t test_app .
docker images
docker run test_app
docker ps -a
Информация о контейнера:
docker container inspect
----

##### В ходе лабораторной работы были получены навыки работы с Docker, изучены основные команды, а также создан собственный образ и контейнер на основе файла с кодом на языке C++, который выводил сообщение в консоль.

