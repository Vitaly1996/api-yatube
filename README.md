### Yatube API
### Описание
В данном проекте разработано API сервиса Yatube

### Технологии
- Python 3.7
- Django 2.2
- Django Rest Framework 3.12.14
- Simple-JWT 5.2.0

### Установка
- склонировать репозиторий
```sh
git clone github.com/Vitaly1996/yatube.git
```
- создать и активировать виртуальное окружение для проекта

```sh
python -m venv venv
source venv/scripts/activate (Windows)    
source venv/bin/activate (MacOS/Linux)
python3 -m pip install --upgrade pip
```
- установить зависимости

```sh
python pip install -r requirements.txt
```
- сделать миграции
```sh
python manage.py makemigrations
python manage.py migrate
```

- запустить сервер
```sh
python manage.py runserver
```

### Пример запросов
* GET   http://127.0.0.1:8000/api/v1/posts/   

<details>
  <summary>Answer</summary>
  
  {
"count": 123,    
"next": "http://api.example.org/accounts/?offset=400&limit=100",    
"previous": "http://api.example.org/accounts/?offset=200&limit=100",    
"results": [{}]    
}
</details>

* POST   http://127.0.0.1:8000/api/v1/follow/ 

<details>
  <summary>Answer</summary>
  
  {
"following": "string"
}
</details>

* POST  http://127.0.0.1:8000/api/v1/jwt/create/

<details>
  <summary>Answer</summary>
  
  {
"username": "string",    
"password": "string"
}
</details>
