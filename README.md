## Kittygram - социальная сеть для обмена фотографиями своих котиков. Написан сервис на Python/Django на стороне backend'a и React/JS - на frontend'e
```
Технологии
- Django 3.2.3
- Django Rest Framework 3.12.4
- Nginx
- Djoser
- Gunicorn
```

# Установка/запуск проекта:

- Клонировать репозиторий:
```
git clone https://github.com/kda99/infra_sprint1.git
```
- Создать/активировать виртуальное окружение из папки infra_sprint1
```
python -m venv venv
venv/Scripts/activate
```
- Установить зависимости из requirements.txt
```
pip install -r requirements.txt
```
- Создать файл .env в папке backend/
```
SECRET_KEY=django-secret-key
DEBUG=False
```
- Выполнить миграции из папки backend/
```
python manage.py migrate
```
- Запустить проект
```
python manage.py runserver
```
