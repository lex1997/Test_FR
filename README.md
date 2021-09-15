
## Как запустить
### Первоначальная установка 
```
cd DRF-Poll-Test
pip install -r requirements.txt
cd backend
python manage.py migrate
python manage.py createsuperuser
```
Создаём супер-юзера с именем admin и паролем admin.
Это имя и пароль будут использоваться в тестах (см. tests/settings.py).

### Запуск сервера
```
cd DRF-Poll-Test/backend
python manage.py runserver
```

### Запуск тестов
Тесты следует запускать при работающем сервере.
```
cd DRF-Poll-Test/tests
pytest
```

## Описание API

См. [API.md](API.md)


## Схема данных

![schema](schema.svg)
