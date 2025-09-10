# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки»  - `Zarubov Nikolay`
---

### Задание 1

`Запустите на своей виртуальной машине два простых сервера Python на разных портах
 Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
 Настройте балансировку Round-robin на 4-м уровне.
 Для проверки отправьте файл конфигурации haproxy и скриншоты, на которых видно перенаправление запросов на разные
 серверы при обращении к HAProxy.`
---

### Ответ 

![redirection](https://raw.githubusercontent.com/nvzar/Clusterization-8-03-hw/main/img/redirection.png)
![redirection](https://raw.githubusercontent.com/nvzar/Clusterization-8-03-hw/main/img/server2.png)
![redirection](https://raw.githubusercontent.com/nvzar/Clusterization-8-03-hw/main/img/server1.png)
![redirection](https://raw.githubusercontent.com/nvzar/Clusterization-8-03-hw/main/img/HAProxy.png)
---

### Задание 2 

`Запустите на своей виртуальной машине три простых сервера Python на разных портах
 Настройте балансировку Weighted Round Robin на 7-м уровне, чтобы первый сервер имел вес 2, второй — 3, а третий — 4
 HAproxy должен балансировать только тот HTTP-трафик, который адресован домену example.local
 Для проверки отправьте файл конфигурации haproxy, а также скриншоты, на которых видно перенаправление запросов на разные
 серверы при обращении к HAProxy с использованием домена example.local и без него.`
---

### Ответ

Файл конфигурации
[haproxy.cfg](https://github.com/nvzar/Clusterization-8-03-hw/blob/main/haproxy.cfg)
---

![redirection](https://raw.githubusercontent.com/nvzar/Clusterization-8-03-hw/main/img/haproxy.cfg.screen.png)

