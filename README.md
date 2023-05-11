# Блог с REST API

## Описание
Блог с REST API и документацией Redoc. CRUD записей через api

Стек: Django Rest Framework, djoser аутентификация по токену, redoc, pagination, permissions, throttling, django_filters.

## Как запустить проект

1. Kлонируем репозиторий
```
git clone 
```

2. Установим и активируем виртуальное окружение
```
python3 -m venv venv
```
```
. venv/bin/activate
```

3. Установим зависимости
```
pip install -r requirements.txt
```

4. Выполним миграции
```
python manage.py migrate
```

5. Запустим проект
```
python manage.py runserver
```
