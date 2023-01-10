### Как запустить проект:

git clone git@github.com:Irya0103/api_final_yatube.git

cd yatibe_api

Cоздать и активировать виртуальное окружение:

python3 -m venv env

source env/bin/activate
. venv/Scripts/activate

python3 -m pip install --upgrade pip

Установить зависимости из файла requirements.txt:
pip install -r requirements.txt

Выполнить миграции:
python3 manage.py migrate

Запустить проект:
python3 manage.py runserver

После запуска проекта по адресу http://127.0.0.1:8000/redoc/ будет доступна СП API с примерами.
