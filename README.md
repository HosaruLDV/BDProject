Проект по БД

По умолчанию программа записывает данные из файла, который можно указать в main.py в блоке elif index == "3" в loader(), там же указывается название таблицы.

В документе loader.py находится функция, которая отвечает за заполнение таблицы suppliers данными из Json документа.

Скрипт на создание таблицы suppliers лежит в файле create_suppliers_table.sql

В документе updater.py находиться функция, которая отвечает за апдейт таблицы products в бд.

В файле getters.py находятся две функции get_product_by_id и get_category_by_id ,функции возвращают данные в виде json-строки.

Основной функционал программы реализован в файле main.py

Скрипты на выборку данных по sql запросам из БД лежит в остальных sql файлах.

В файле script.json лежат данные для подключения к БД
