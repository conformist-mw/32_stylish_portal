# Shared CSS Library

В файле `nginx.conf` содержится конфигурация двух сайтов с подменой главного файла стилей.

# How to Test

Для тестирования нужно установить `nginx`, например так:

```bash
$ sudo apt install nginx
```

склонировать этот репозиторий, перейти в его каталог и выполнить команды:

```bash
$ sudo ln -s $(pwd)/nginx.conf /etc/nginx/nginx.conf
$ sudo systemctl restart nginx.service
```

Сайты доступны по адресам:

- [первый](http://127.0.0.1:8081)
- [второй](http://127.0.0.1:8082)

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
