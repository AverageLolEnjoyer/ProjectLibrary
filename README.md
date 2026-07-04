# Система Библиотеки

Веб-приложение для управления библиотекой вуза. Позволяет библиотекарям добавлять книги, выдавать их студентам и отслеживать задолженности. Студенты могут искать книги и смотреть список взятых изданий.

## Технологии

- Python + Django 
- SQLite 
- HTML + CSS 

## Функции

### Библиотекарь
- Добавление новых книг в каталог
- Выдача книг студентам
- Просмотр списка студентов и взятых ими книг
- Поиск книг по названию или автору

### Студент
- Поиск книг
- Просмотр своих взятых книг и дат возврата

## Как запустить

```bash
git clone https://github.com/AverageLolEnjoyer/KursovayaWEB
cd KursovayaWEB
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
