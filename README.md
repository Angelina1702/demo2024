##1.
**Цель задания:**
1. Выполните базовую настройку всех устройств:  
	a. Соберите топологию согласно рисунку. Все устройства работают на OC Linux - Debian  
  b. Присвоить имена в соответствии с топологией  
  c. Рассчитайте IP-адресацию IPv4 и IPv6. Необходимо заполнить таблицу №1. При необходимости отредактируйте таблицу.  
  d. Пул адресов для сети офиса BRANCH - не более 16. Для IPv6 пропустите этот пункт.  
  e. Пул адресов для сети офиса HQ - не более 64. Для IPv6 пропустите этот пункт.  
# demo2024
| Имя устройств | Интерфейс | Ipv4/IPv6   |Маска Префикс   |Шлюз|
| ----------- | ----------- | ---------   | -----------    | -- |
|ISP            | ens18     |10.10.201.100|/24 255.255.255.0|10.10.201.254|
|              | ens19     |192.168.0.165|/30 255.255.255.2|
|HQ-R|           ens20      |192.168.0.161|/30 255.255.255.252|
 |  |               ens21       |192.168.0.129|/27 255.255.255.224| |
|сергей|ens19         |192.168.0.162|/30 255.255.255.252| |
|HQ-SRV|ens19            |192.168.0.1  |/25 255.255.255.128| |
|BR-SRV|ens19           |192.168.0.166|/30 255.255.255.224| |
пепса


![278255735-c5ae32a9-a995-4bf7-9e46-b6b17f77c55c](https://github.com/Angelina1702/demo2024/assets/148867681/36e2a615-12ea-4bca-9e76-43bf44e13880)
