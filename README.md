# API для "Yatube"
## Описание:
Данный проект - API для сервиса [Yatube](https://github.com/DenisShahbazyan/hw05_final).

## Развертывание:
### Запуск веб-сервера::
- Склонируйте проект на Ваш компьютер 
```sh 
git clone https://github.com/DenisShahbazyan/api_final_yatube.git
``` 
- Перейдите в папку с проектом 
```sh 
cd api_final_yatube
``` 
- Создайте и активируйте виртуальное окружение 
```sh 
python -m venv venv 
source venv/Scripts/activate 
``` 
- Обновите менеджер пакетов (pip) 
```sh 
pip install --upgrade pip 
``` 
- Установите необходимые зависимости 
```sh 
pip install -r requirements.txt
``` 
-   Создайте миграции
```sh
python ./yatube/manage.py makemigrations
python ./yatube/manage.py migrate
```
-   Создайте суперпользователя
```sh
python ./yatube/manage.py createsuperuser
```
-   Запуск сервера
```sh
python ./yatube/manage.py runserver
```
-   Сайт запуститься по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000/)

## Системные требования:
- [Python](https://www.python.org/) 3.10.4

## Планы по доработке:
>Проект сделан в учебных целях, доработка не планируется.

## Используемые технологии:
- [Django](https://www.djangoproject.com/) 2.2.16
- [Django REST framework](https://www.django-rest-framework.org/) 3.12.4
- [djoser](https://djoser.readthedocs.io/en/latest/getting_started.html) 2.1.0

## Авторы:
- [Denis Shahbazyan](https://github.com/DenisShahbazyan)

## Лицензия:
- MIT