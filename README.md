# Тестовое задание на позицию стажера backend в юнит Geo

Цель задания – разработать приложение имплементацию in-memory [Redis](https://redis.io/) кеша.

Детали реализации:
* Писать код можно на любом языке программирования
* Предоставить инструкцию по запуску приложения. В идеале (но не обязательно) – использовать контейнеризацию с возможностью запустить проект командой `docker-compose up`
* Финальную версию нужно выложить на github.com (просьба не делать форк этого репозитория, дабы не плодить плагиат)

Необходимы функционал:

* Клиент и сервер tcp(telnet)/REST API
* Key-value хранилище строк, списков, словарей
* Возможность установить TTL на каждый ключ
* Реализовать операторы: GET, SET, DEL, KEYS
* Реализовать покрытие несколькими тестами функционала

Дополнительно (необязательно):

* Реализовать операторы: HGET, HSET, LGET, LSET
* Реализовать сохранение на диск
* Масштабирование (на серверной или на клиентское стороне)
* Авторизация
* Нагрузочные тесты

Справка:

Описание Redis-команд можно найти [здесь](https://redis.io/commands)



