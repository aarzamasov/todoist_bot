# Telegram Todoist Bot

## Описание

Telegram Todoist Bot — это автоматизированный бот для Telegram, предназначенный для добавления задач в Todoist прямо из вашего Telegram чата. Этот проект позволяет пользователям быстро и эффективно управлять своим списком задач без необходимости переключаться между приложениями.

## Функционал

- Добавление задач в Todoist через Telegram.
- Автоматический перезапуск после сбоев для непрерывной работы.

## Технологии

- Node.js
- Telegram Bot API
- Todoist API
- Docker

## Начало работы

### Предварительные требования

- Учетная запись на [Telegram](https://telegram.org/) для создания бота
- Учетная запись на [Todoist](https://todoist.com/) для получения API токена
- Установленный [Docker](https://www.docker.com/) (для запуска в контейнере)

### Установка и запуск
<<<<<<< HEAD

    docker run -d --restart always -e TELEGRAM_TOKEN=ваш_токен_бота -e TODOIST_TOKEN=ваш_todoist_токен dzarlax/todoist_bot
=======
docker run -d --restart always -e TELEGRAM_TOKEN=ваш_токен_бота -e TODOIST_TOKEN=ваш_todoist_токен telegram-todoist-bot
>>>>>>> 2ab11ef (Readme fix)

## Как использовать

Отправьте или перешлите любое текстовое сообщение боту в Telegram, и оно будет автоматически добавлено в ваш список задач Todoist. При пересылке сообщения - будет указан username автора.

