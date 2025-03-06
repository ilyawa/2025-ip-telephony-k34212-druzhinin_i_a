University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)
Year: 2024/2025
Group: K34212
Author: Druzhinin Ilya Antonovich
Lab: Lab1
Date of create: 02.03.2025
Date of finished: 02.03.2025 

## Лабораторная работа №1 "Базовая настройка ip-телефонов в среде Сisco packet tracer"

## Описание

Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены и настроены все узлы устройств.

## Цель работы

Изучить рабочую среду Cisco Packet Tracer, ознакомить- ся с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.

## Ход работы  
### Часть 1
Соберём схему соединения по заданию.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-02%20at%2015.58.43.png">  
<br></br>  

Пропишем на каждом компьютере ip-адрес из одной локальной подсети.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-02%20at%2016.05.44.png">  
<br></br>  

После этого между компьютерами появляется связь.

<img width="800" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-02%20at%2016.06.37.png">

### Часть 2

Соберем новую схему соединения по заданию.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-06%20at%2012.47.33.png">  
<br></br>  

Настроим CMERouter. Выдадим роутеру ip-адрес 192.168.0.1, настроим на роутере dhcp-сервер с пулом 192.168.0.1/24. Далее укажем ip-адрес роутера, как адрес TFTP-сервера, что нужно для настройки ip-телефонии. Командой max-dn 10 настроим максимальное количество телефонных номеров на маршрутизаторе, командой max-ephones - максимальное количество ip-телефонов. Команда auto-assign позволяет автоматически назначить номера для ephones. Для ephone-dn 1 назначим телефонный номер 111, а для ephone-dn 2 - 222.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-06%20at%2012.52.17.png">  
<br></br>

Настроим коммутатор. Назначим одинаковый voice vlan для каждого порта коммутатора.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-06%20at%2012.55.08.png">  
<br></br>  

Как можно видеть, каждый телефон получил ip-адрес.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-06%20at%2012.56.19.png">  
<br></br> 

Как результат работы, появилась связь между телефонами.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-06%20at%2012.57.20.png">
<img width="200" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab1/images/Screen%20Shot%202025-03-06%20at%2012.57.36.png">  
<br></br> 

## Вывод
Таким образом, была произведена базовая настройка ip-телефонов в среде Cisco packet tracer.
