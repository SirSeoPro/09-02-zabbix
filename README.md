# Домашнее задание к занятию «Система мониторинга Zabbix» - Koshcheev Ivan

### Задание 1 

Установите Zabbix Server с веб-интерфейсом.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите PostgreSQL. Для установки достаточна та версия, что есть в системном репозитороии Debian 11.
3. Пользуясь конфигуратором команд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.
4. Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server.

#### Требования к результаты 
1. Прикрепите в файл README.md скриншот авторизации в админке.
2. Приложите в файл README.md текст использованных команд в GitHub.

<details>

![image1](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/1-1.png)
![image2](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/1-2.png)
![image3](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/1-3.png)

</details>

---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
1. Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 вирт.машины, одной из них может быть ваш Zabbix Server.
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов.
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera.
5. Проверьте, что в разделе Latest Data начали появляться данные с добавленных агентов.

#### Требования к результаты 
1. Приложите в файл README.md скриншот раздела Configuration > Hosts, где видно, что агенты подключены к серверу
2. Приложите в файл README.md скриншот лога zabbix agent, где видно, что он работает с сервером
3. Приложите в файл README.md скриншот раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.
4. Приложите в файл README.md текст использованных команд в GitHub

<details>

![image4](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/2-1.png)
![image5](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/2-2.png)
![image6](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/2-3.png)
![image7](https://github.com/SirSeoPro/09-02-zabbix/blob/main/img/2-4.png)

#### Bash commands:

```
git clone git@github.com:SirSeoPro/09-02-zabbix.git
git add img/
git commit -m "add_img"
git push

```
</details>

---
## Задание 3 со звёздочкой*
Установите Zabbix Agent на Windows (компьютер) и подключите его к серверу Zabbix.

#### Требования к результаты 
1. Приложите в файл README.md скриншот раздела Latest Data, где видно свободное место на диске C:
--- 

## Критерии оценки

1. Выполнено минимум 2 обязательных задания
2. Прикреплены требуемые скриншоты и тексты 
3. Задание оформлено в шаблоне с решением и опубликовано на GitHub
