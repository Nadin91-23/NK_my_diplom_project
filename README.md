﻿## Приложение - Яндекс Самокат

#### _Яндекс Самокат — это сервис, который позволяет арендовать электрический самокат на несколько дней._
_У сервиса есть веб-приложение, мобильное приложение и API._

### Технологии

- Язык приложения — JavaScript.
- Выполняется в среде Node.js v12.17.0.
- Доступ к приложению по протоколу HTTP 1.1.

## Проверяемые API

#### В приложении проверяется, что по треку заказа можно получить данные о заказе.
 Для этого используются:
 - создание методом POST нового заказа – ручка /api/v1/orders;
 - сохранение трека данного заказа;
 - выполнение запроса на получение заказа по треку методом GET – ручка /api/v1/orders/track.
 
#### Составленный тест напрвлен на проверку соответствия статуса запроса коду 200. 

## Запуск тестов
- #### Для запуска тестов должны быть установлены пакеты pytest и requests
- #### Запуск всех тестов выполянется командой pytest