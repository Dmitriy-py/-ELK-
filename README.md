# Домашнее задание к занятию «ELK»

## ` Дмитрий Климов `

## Задание 1. Elasticsearch

### Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

## Ответ:

![Снимок экрана (1108)](https://github.com/user-attachments/assets/ea836373-40b6-48c8-b912-513990f287b5)

![Снимок экрана (1109)](https://github.com/user-attachments/assets/ac8d2682-ecd9-480b-a2b4-f323787d93b2)

## Задание 2. Kibana

### Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

## Ответ:

![Снимок экрана (1110)](https://github.com/user-attachments/assets/c5a63f71-cade-46e4-9c0f-1709d4c475fe)

![Снимок экрана (1113)](https://github.com/user-attachments/assets/a035eefb-8d83-460a-9e8e-7cf0781ccbe3)


## Задание 3. Logstash

### Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

## Ответ:

![Снимок экрана (1118)](https://github.com/user-attachments/assets/116ba235-88c7-4397-a04b-32b397f8b2cf)

![Снимок экрана (1117)](https://github.com/user-attachments/assets/a0f82dde-b41b-4f88-b9e0-e0bfe863ece8)

![Снимок экрана (1116)](https://github.com/user-attachments/assets/1b8a0f9b-fdef-4f90-9eae-629010a8d878)


## Задание 4. Filebeat.

### Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

![Снимок экрана (1121)](https://github.com/user-attachments/assets/cdc5d97e-9e2e-45fa-a2ad-74ec947911e0)

![Снимок экрана (1120)](https://github.com/user-attachments/assets/b4664f4e-c121-49af-84e0-3889d46dd099)



