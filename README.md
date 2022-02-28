# README #

Система телеметрии матрикс (далее СТМ). Предназначена для опроса различных объектов учета энергоресурсов.

### Требования ###

Для запуска СТМ необходимы

* Брокер сообщений [RabbitMQ](https://www.rabbitmq.com/)
* Базы данных:
* 1. [MSSQL](https://www.microsoft.com/ru-ru/sql-server/sql-server-downloads)/[PostgreSQL](https://www.postgresql.org/download/)
* 2. [Neo4j](http://neo4j.com/)
* 3. [Redis](https://github.com/microsoftarchive/redis/releases/tag/win-3.0.504)

### Запуск системы###

* Веб-сервер Matrix.Web.Host
* Сервер опроса Matrix.Poll.Server

Дополнительные сервисы

* Сервер расписания Matrix.Scheduler
* Сервер наблюдатель Matrix.CheckServer

