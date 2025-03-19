# pymongo-api

## Как запустить

Запускаем шардированный mongodb, с кэшом и приложение

```shell
docker compose up -d
```

Заполняем mongodb данными

```shell
./scripts/mongo-init.sh
```

## Как проверить

### Если вы запускаете проект на локальной машине

Откройте в браузере http://localhost:8080/helloDoc/users

### Если вы запускаете проект на предоставленной виртуальной машине

Узнать белый ip виртуальной машины

```shell
curl --silent http://ifconfig.me
```

Откройте в браузере http://<ip виртуальной машины>:8080

## Доступные эндпоинты

Список доступных эндпоинтов, swagger http://<ip виртуальной машины>:8080/docs## Доступные эндпоинты

## Схема решения 

[Решение 1,5,6](https://drive.google.com/file/d/1wUzCzJpfPicW6jaGQCdlYiMI8wseZBRK/view?usp=sharing)