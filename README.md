# Описание


В данном проекте разработано API сервиса Yatube, чтобы еще в большей степени порадовать дорогих пользователей Yatube!
____
# Как запустить проект:
### Клонировать репозиторий и перейти в него в командной строке:

git clone git@github.com:Vitaly1996/api_final_yatube.git
____
### Cоздать и активировать виртуальное окружение:

python -m venv venv

source env/bin/activate

python3 -m pip install --upgrade pip
____
### Установить зависимости из файла requirements.txt:

pip install -r requirements.txt
____
### Выполнить миграции:

python3 manage.py migrate
____
### Запустить проект:

python3 manage.py runserver

# Пример запросов

black_square_button: GET   'http://127.0.0.1:8000/api/v1/posts/'    


'Answer:'
{
"count": 123,    
"next": "http://api.example.org/accounts/?offset=400&limit=100",    
"previous": "http://api.example.org/accounts/?offset=200&limit=100",    
"results": [{}]    
}
