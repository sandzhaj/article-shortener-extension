# "Короче, Склифосовский!" v0.3

[![Watch the video](https://img.youtube.com/vi/8vFjYYKZjvE/maxresdefault.jpg)](https://youtu.be/E_oO9iFZzWY)

Расширение для браузеров на основе Сhromium, автоматизирующее работу с сокращателем статей от Яндекса https://300.ya.ru/, который использует YandexGPT<br>
Необходима учётная запись Яндекс.

## Установка
[Установка из интернет-магазина Chrome](https://chrome.google.com/webstore/detail/%D0%BA%D0%BE%D1%80%D0%BE%D1%87%D0%B5-%D1%81%D0%BA%D0%BB%D0%B8%D1%84%D0%BE%D1%81%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B9/mpaebgncookaokflfdhflpmhpimkfeii)<br>
ИЛИ<br>
Установка из GitHub (содержит самые последние изменения)
1. [Скачать](https://github.com/nicodimuscanis/article-shortener-extension/archive/refs/heads/master.zip) и распаковать
2. В браузере на странице: `chrome://extensions` включить режим разработчика и нажать на "загрузить распакованное расширение"
3. Выбрать папку `src` из распакованных файлов

## Настройка
К сожалению, Яндекс не позволяет использовать сервис без авторизации, т.е. нужна учётная запись или валидный токен<br>
Для работы расширения достаточно просто войти в учётную запись Яндекс.

Для того чтобы пользоваться сервисом без входа в учётную запись, необходимо получить токен.<br>
Внимание: на данный момент (30.06.23) это бета версия сервиса от Яндекс и шаги ниже могут быть не актуальными<br>
1. Получить [токен](https://oauth.yandex.ru/authorize?response_type=token&client_id=702a61748ec947a4b1ab467d2b2f3edb)
2. Скопировать токен и вставить на странице настройки расширения

## Использование
На странице статьи, из которой нужно выделить суть, нажать на иконку расширения в браузере.
После обработки произойдёт перенаправление на страницу с укороченной версией (или откроется в новой вкладке, взависимости от настоек).
Также работает со страницами не на русском языке.

## Ограничения и замечания
1. Статья должна быть не больше 30 тыс. символов и быть информационной, т.е. со стихами и художественными произведениями может либо не работать, либо работать весьма странно.
2. По поводу качества сокращённых статей все вопросы к Яндексу. Я не имею к Яндексу никакого отношения.
3. Для пересказа статей, не опубликованных в сети, можно развернуть собственный сервис, который создаёт ссылку на пользовательский контент, наприер https://github.com/nicodimuscanis/make-page

[Журнал изменений](https://htmlpreview.github.io/?https://github.com/nicodimuscanis/article-shortener-extension/blob/master/src/changelog.html)

Распространяется под [лицензией MIT](https://github.com/nicodimuscanis/article-shortener-extension/blob/master/LICENSE.md)

