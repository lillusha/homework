# Домашнее задание к занятию 2 "Кластеризация и балансировка нагрузки" - "Корягин Николай" 

------

### Задание 1
- Запустите два simple python сервера на своей виртуальной машине на разных портах
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

### Решение 1 

![image](https://github.com/lillusha/homework/blob/main/img/haproxy1.1.png)
![image](https://github.com/lillusha/homework/blob/main/img/haproxy1.2.png)
![image](https://github.com/lillusha/homework/blob/main/img/haproxy1.3.png)

### Задание 2
- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

### Решение 2 

![image](https://github.com/lillusha/homework/blob/main/img/haproxy2.1.png)
![image](https://github.com/lillusha/homework/blob/main/img/haproxy2.2.png)
![image](https://github.com/lillusha/homework/blob/main/img/haproxy2.3.png)
