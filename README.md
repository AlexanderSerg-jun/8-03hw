# Домашнее задание к занятию "`Система мониторинга Zabbix`" - `Савин Александр`



---

### Установите Zabbix Server с веб-интерфейсом.

`Процесс выполнения`
1. `Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.`
2. `Установите PostgreSQL. Для установки достаточна та версия, что есть в системном репозитороии Debian 11.`
3. `Пользуясь конфигуратором команд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.`
4. `Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server.`
`Все действия выполнялись на виртуальной машине с адресом 192.168.0.107`

`![Авторизация в zabbix админке](https://github.com/AlexanderSerg-jun/8-03hw/img/zabbix_admin.png)`


---

### Задание 2

`Установите Zabbix Agent на два хоста.`

`Процесс выполнения`
1. `Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.`
2. `Установите Zabbix Agent на 2 вирт.машины, одной из них может быть ваш Zabbix Server.`
3. `Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов.`
4. `Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera.`
5. `Проверьте, что в разделе Latest Data начали появляться данные с добавленных агентов.`

`Из-за отсутствия мощностей  zabbix-agent установлен на машине zabbix-server и еще одной виртуальной машине`





![Добавленые хосты](https://github.com/AlexanderSerg-jun/8-03hw/img/configuration_hosts.png)`
![Логи zabbix agent](https://github.com/AlexanderSerg-jun/8-03hw/img/log_zabbix.png)`
![Последние данные](https://github.com/AlexanderSerg-jun/8-03hw/img/Latest_data.png)`

---

`Команды использованные для github`
1. `git add .`
2. `git сommit`
3. `git push`