University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)  
Year: 2024/2025  
Group: K34212  
Author: Druzhinin Ilya Antonovich  
Lab: Lab2  
Date of create: 09.03.2025  
Date of finished: 09.03.2025   

## Лабораторная работа №2 "Конфигурация voip в среде Сisco packet tracer"

## Описание

Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены все узлы устройств. Предварительно удалить все преды- дущие конфигурационные файлы на маршрутизаторах Cisco 2811, на коммутаторе Cisco catalyst 3560.  

## Цель работы

Иизучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.  

## Ход работы  
### Часть 1

По заданию была собрана следующая схема сети.

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2015.42.45.png">  
<br></br>   

Затем на маршрутизаторе были прописаны следующие настройки: был отключен DNS, заданы пароли для 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2015.43.23.png">  
<img width="400" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2015.44.57.png">   
<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2015.47.07.png">  
<img width="500" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2016.03.05.png">  
<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2016.08.16.png">  
<br></br>  

Далее был настроен коммутатор.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2016.12.43.png">  
<br></br>  

Телефоны получили ip-адреса из пула dhcp.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2016.13.00.png">  
<br></br>  

Пример успешного звонка с телефона 2 на телефон 1 для проверки связи.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2016.13.35.png">  
<br></br>  

### Часть 2

Во второй части работы требуется собрать схему сети с ip-телефонами в качестве соединяющего звена между коммутатором и компьютерами.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-11%20at%2014.39.33.png">  
<br></br>  

Настроим коммутатор. Создадим vlan для ip-телефонии и vlan для компьютеров.

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2017.49.09.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2018.04.05.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2018.04.17.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2019.39.31.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2019.39.46.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2019.41.09.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2019.41.47.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2019.41.56.png">  
<br></br> 

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab2/images/Screen%20Shot%202025-03-09%20at%2019.42.22.png">  
<br></br> 

## Вывод
Таким образом, был изучен процесс построения сети voIP с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.
