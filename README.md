# ��������


� ������ ������� ����������� API ������� Yatube, ����� ��� � ������� ������� ���������� ������� ������������� Yatube!
____
# ��� ��������� ������:
### ����������� ����������� � ������� � ���� � ��������� ������:

git clone git@github.com:Vitaly1996/api_final_yatube.git
____
### C������ � ������������ ����������� ���������:

python -m venv venv

source env/bin/activate

python3 -m pip install --upgrade pip
____
### ���������� ����������� �� ����� requirements.txt:

pip install -r requirements.txt
____
### ��������� ��������:

python3 manage.py migrate
____
### ��������� ������:

python3 manage.py runserver

# ������ ��������

GET   'http://127.0.0.1:8000/api/v1/posts/'


'Answer:'
{
"count": 123,
"next": "http://api.example.org/accounts/?offset=400&limit=100",
"previous": "http://api.example.org/accounts/?offset=200&limit=100",
"results": [
{}
]
}
