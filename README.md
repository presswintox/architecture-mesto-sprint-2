# pymongo-api

## Как запустить

Перейдите в папку с нужным проектом

```shell
cd mongo-sharding
cd mongo-sharding-repl
cd sharding-repl-cache
```

Запускаем mongodb и приложение

```shell
docker compose up -d
```

Инициализация шардирования,репликации и заполнение бд

```shell
./scripts/mongo-init.sh
```

Если при инициализации шардирования вы получаете ошибки, то попробуйте очистить окружение и запустить инициализацию заново.

Очистка docker окружения
```shell
docker-compose down -v
```

## Как проверить

### Если вы запускаете проект на локальной машине

Откройте в браузере http://localhost:8080

## Доступные эндпоинты

Список доступных эндпоинтов, swagger http://localhost:8080/docs