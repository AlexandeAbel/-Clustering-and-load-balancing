# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки»

**Задание 1**
*Запустите два simple python сервера на своей виртуальной машине на разных портах*
*Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке*
*Настройте балансировку Round-robin на 4 уровне.*
*На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление *запросов на разные серверы при обращении к HAProxy.*

![1.1](https://github.com/AlexandeAbel/-Clustering-and-load-balancing/blob/main/img/1.1.bmp)

![1.2](https://github.com/AlexandeAbel/-Clustering-and-load-balancing/blob/main/img/1.2.bmp)

![1.3](https://github.com/AlexandeAbel/-Clustering-and-load-balancing/blob/main/img/1.3.bmp)

**Задание 2**
*Запустите три simple python сервера на своей виртуальной машине на разных портах.*
*Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4*
*HAproxy должен балансировать только тот http-трафик, который адресован домену example.local*
*На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.*
*Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.*

![2.1](https://github.com/AlexandeAbel/hw-03/blob/main/img/2.1.bmp)

![2.2](https://github.com/AlexandeAbel/hw-03/blob/main/img/2.2.bmp)

![2.3](https://github.com/AlexandeAbel/hw-03/blob/main/img/2.3.bmp)
