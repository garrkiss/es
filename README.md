# Домашнее задание к занятию "`«ELK»`" - `Бакулев Евгений`

### Задание 1
### Что нужно сделать:

1. Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

### Решение 1

![Скрин](https://github.com/garrkiss/es/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2007.07.24_12.17.19.png)

### Задание 2
### Что нужно сделать:

1. Установите и запустите Kibana.
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

### Решение 2

![Скрин](https://github.com/garrkiss/es/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2007.07.24_12.19.12.png)

### Задание 3
### Что нужно сделать:

1. Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Решение 3

![Скрин](https://github.com/garrkiss/es/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2007.07.24_13.56.43.png)

### Задание 4
### Что нужно сделать:

1. Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

### Решение 4

![Скрин](https://github.com/garrkiss/es/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2007.07.24_14.02.53.png)
