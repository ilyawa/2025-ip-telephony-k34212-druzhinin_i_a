University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)  
Year: 2024/2025  
Group: K34212  
Author: Druzhinin Ilya Antonovich  
Lab: Lab3  
Date of create: 02.03.2025  
Date of finished: 02.03.2025   

## Лабораторная работа №3 "Использование Asterisk в качестве SIP proxy"

## Описание

Для выполнения данной лабораторной работы необходимо выполнить настройку Asterisk.

## Цель работы

Изучить программный комплекс Asterisk. Настройка Asterisk для локальных звонков.

## Ход работы

Установим на систему Asterisk.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2015.25.16.png">
<br></br>

Установим twinkle в качестве клиента для звонков.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2015.26.41.png">
<br></br>

Пропишем настройки для двух "телефонов" с номерами 1000 и 2000.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2015.53.15.png">
<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2015.58.29.png">
<br></br>

Перезапустим Asterisk.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2015.59.32.png">
<br></br>

Создадим профили в Twinkle.  

<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2016.01.25.png">
<img width="600" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2016.03.07.png">
<br></br>

Пример успешного звонка с номера 2000 на номер 1000. Для корректной работы требовалось создать 2 инстанса программы Twinkle. Asterisk работал на порту 5060, телефон 1000 на 5061 и телефон 2000 на 5062.  

<img width="500" src="https://github.com/ilyawa/2025-ip-telephony-k34212-druzhinin_i_a/blob/main/lab3/images/Screen%20Shot%202025-03-13%20at%2017.46.39.png">
<br></br>
  
## Вывод
Таким образом, была произведена базовая настройка Asterisk в качестве SIP-proxy, был произведен тестовый звонок между двумя sip-телефонами.
