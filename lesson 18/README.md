## Задание 1(Minimum):
Создать на jenkins сервере freestyle project который:
* Делает pull с репозитория. 
* Собирает docker image использует Dockerfile c 4 ДЗ и делает push в docker repo (репозиторий на ваше усмторение)

### Для выполения задания вам нужно:
* Создать проект в одном и SCV(GitHub, GitLab, etc.)
* Сделать 4 ДЗ если оно было не сделано ранее
* Запушить Dockerfile и всё что нужно для работы в новый репозиторий
* Добавить публичный ключ Jenkins, к своему репозитори
* Создать публичный Docker репозиторий
* Создать freestyle project который будет иметь доступ к вашему репо и к вашему docker репозиторию
* Запустить билд и в результате получить docker image в вашем docker repo

### Результат выполеного задания 1:
* ПР с файлом который содержит имя вашего docker image.`(Пример: 683038831899.dkr.ecr.eu-west-2.amazonaws.com/vadym.tyshchenko:latest)`
* Имя вашего проекта в Jenkins
* Freestyle project должен выполнять по нажатию на кпоку "Start build" весь выше описаный процесс.

### Tip's:
* Можете устанавливать и использовать любые плагины на ваше усмотрение
* Репозиторий на ваше усмотрение
* Не удалять чужие проекты в Jenkins
* Креды до Jenkins сервера будут доступны в Slack
* Проекты в Jenkins обзывать по формату: **name.surname**

## Задание 2(Recommended):
* Сделаное задание 1
* Приложение должно быть доступным с "мира"(Ментор может проверить работу docker контейнера через браузер)

### Для выполения задания 2 вам нужно:
* Установить docker-сe ,если до этого момента никто это не сделал, на сервере 35.180.190.249
* Создать свой деплоймент и запустить свой docker image с вашего docker репозитория. 
* Дописать Jenkins freestyle project

### Tip's:
* На серевере для проверки работы веб приложения открытые порты с 3000 по 3100
* ssh доступ к серверу для деплоя открыт для Jenkins сервера от пользователя *jenkins*

### Результат выполеного задания 2:
* Ссылка на ваше веб приложение
* Имя вашего проекта в Jenkins
* Freestyle project должен не иметь ошибок в процессе работы

# Deadline: 16:00 09.03.2021
P.S. Без исключений :) 
