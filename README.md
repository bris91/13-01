# Домашнее задание к занятию "Уязвимости и атаки на информационные системы" - `Lebedev Boris`

# Задание 1
Скачайте и установите виртуальную машину Metasploitable: https://sourceforge.net/projects/metasploitable/.
Это типовая ОС для экспериментов в области информационной безопасности, с которой следует начать при анализе уязвимостей.
Просканируйте эту виртуальную машину, используя nmap.
Попробуйте найти уязвимости, которым подвержена эта виртуальная машина.
Сами уязвимости можно поискать на сайте https://www.exploit-db.com/.
Для этого нужно в поиске ввести название сетевой службы, обнаруженной на атакуемой машине, и выбрать подходящие по версии уязвимости.
Ответьте на следующие вопросы:

Какие сетевые службы в ней разрешены?
Какие уязвимости были вами обнаружены? (список со ссылками: достаточно трёх уязвимостей)

`Обнаружены уязвимости:
vsftpd 2.3.4 https://www.exploit-db.com/exploits/17491
ProFTPD 1.3.1 https://www.exploit-db.com/exploits/32798
PostgreSQL DB 8.3.0 - 8.3.7 https://www.exploit-db.com/exploits/32849
                            https://www.exploit-db.com/exploits/32847`

![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/1.1.png)
![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/1.2.png)
![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/1.3.png)
![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/1.4.png)



# Задание 2
Проведите сканирование Metasploitable в режимах SYN, FIN, Xmas, UDP.
Запишите сеансы сканирования в Wireshark.
Ответьте на следующие вопросы:
Чем отличаются эти режимы сканирования с точки зрения сетевого трафика?
Как отвечает сервер?
Приведите ответ в свободной форме.

![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/2.1.png)
![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/2.2.png)
![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/2.3.png)
![alt text](https://github.com/bris91/13-01/blob/96057df76bfbc765cd5a37c952929a3976ddffe7/2.4.png)
