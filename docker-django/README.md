# docker-django

### Локальная среда
- docker 19.03
- docker-compose 1.27.4
- git 2.17

### Среда для создания
- Python 3.8.5
- MySQL 8.0
- nginx 1.18

### Создание службы
```
$ docker-compose build
```

### Создание и запуск контейнера
```
$ docker-compose up
```

### Подключиться к контейнеру приложения
```
$ docker-compose exec app bash
```

### Django установить команду
```
$ docker-compose exec app django-admin.py startproject app .
```
