# Telegram-бот для Магазина Кроссовок

Этот проект представляет собой Telegram-бот для онлайн-магазина кроссовок, разработанный с использованием библиотеки Aiogram и асинхронной базы данных SQLite.

## Описание

Бот позволяет пользователям просматривать каталог товаров, выбирать категории и товары, а также получать информацию о каждом товаре. Проект построен на архитектуре с разделением логики по модулям для обеспечения удобства поддержки и расширения функциональности.

## Функциональность

- Приветственное сообщение при старте.
- Просмотр каталога товаров с выбором категории.
- Просмотр списка товаров в выбранной категории.
- Просмотр подробной информации о товаре (название, описание, цена).
- Навигация с использованием встроенных кнопок и инлайн-клавиатур.

## Технологии

- **Python**
- **Aiogram** (Telegram Bot API)
- **SQLAlchemy** (Асинхронная ORM для работы с базой данных)
- **SQLite** (Асинхронная база данных)
- **Asyncio** (Асинхронное программирование)



## Как использовать

1. Запустите бота и отправьте команду `/start`, чтобы начать работу.
2. Нажмите кнопку **"Каталог"**, чтобы просмотреть доступные категории товаров.
3. Выберите категорию, чтобы увидеть список товаров.
4. Выберите товар, чтобы получить его описание и цену.


