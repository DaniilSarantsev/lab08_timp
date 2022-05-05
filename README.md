----
## Работа с Docker
----
docker run ubuntu echo 'hello from ubuntu'
----

Сборка и настройка собственного образа и контейнера Docker:
docker build -t test_app .
docker images
docker run test_app
docker ps -a
Информация о контейнера:
docker container inspect

