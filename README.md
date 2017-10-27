# Тестовое задание
1. Вам необходимо клонировать данный репозиторй к себе на локальный web-сервер.
2. Создать два `action` для контроллера `task` с именами `front` и `back`.
3. На странице `front` отобразить таблицу с данными взятых с `https://www.express.ru/public/tasks/table.jsonp`.
    1. Сделать возможность сортировки по любому полю (на ваш выбор).
    2. Загрузка страницы не должна ждать результатов запроса.
    3. По возможности визуально дать понять пользователю о работе скрипта и наполнению таблицы данными.
4. На странице `back` показать html-форму с полем ввода адреса (город + улица + здание). При отправке формы на языке `PHP` с помощью сервиса `https://tech.yandex.ru/maps/` определить координаты адреса и отобразить их.
    1. Будет плюсом, если в данной цепочке действий запрос к скрипту `PHP` будет асинхронным и без перезагрузки страницы.
    2. Будет плюсом, если данные координаты адреса будут отображены на карте с помощью `Yandex Maps API`.
5. Залить работу на `https://github.com/` и прислать письмо на почту `i@express.ru` с темой письма `Разработчик. Тестовое задание` и ссылкой на репозиторий.

## Примечание
Если задание выше кажется простым, предлагается реализовать полноценный модуль для фреймворка с последуещей возможностью расширения методов, целью которого будет геокодирование:
- адресов по координатам
- координат по адресу, почтовому отделению

Выполнение тестового задания разрешено в вольном исполнении. Документирование кода обязательно.
