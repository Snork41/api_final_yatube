# API для Yatube
### Описание:
API сервис для соц. сети Yatube
### Технологии:
Python 3.9
Django 3.2
DRF 3.12

### Установка:
- Клонируйте репозиторий и перейдите в него в командной строке:
    ```
    git clone https://github.com/Snork41/api_final_yatube.git
    ```
    ```
    cd api_final_yatube
     ```
- Cоздайте и активируйте виртуальное окружение:
    ```
    python3 -m venv venv
     ```
    ```
    source venv/bin/activate
     ```
- Установите зависимости из файла __requirements.txt__ :
    ```
    pip install -r requirements.txt
    ````
- Выполните миграции::
    ```
    python3 manage.py migrate
    ```
- Запустите проект:

    ```
    python3 manage.py runserver
    ```
- Документация API доступна по адресу http://127.0.0.1:8000/redoc/ 
---
#### Автор
_Максим Давлеев_
