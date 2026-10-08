# CPPK Helpdesk Bot & WebApp

Telegram-бот для автоматизации обработки обращений пользователей с интерфейсом WebApp и классификацией текста через GigaChat API.

## Функционал
* Прием заявок через мини-приложение (Telegram WebApp).
* NLP-анализ обращений с помощью GigaChat API (категория и приоритет).
* Маршрутизация заявок в группы Telegram.

## Стек технологий
* Python 3.10+
* aiogram 3.x
* GigaChat SDK
* HTML5, CSS3, JavaScript (Telegram WebApp)

## Установка и запуск
1. Клонировать репозиторий:
   git clone git@github.com:N30N41KS/CPPK-BOT.git
   cd CPPK-BOT
2. Установить зависимости:
   pip install -r requirements.txt
3. Создать файл .env:
   BOT_TOKEN=твой_токен
   GIGACHAT_CREDENTIALS=твой_ключ
4. Запустить:
   python main.py

