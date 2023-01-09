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

pip install djoser djangorestframework-simplejwt==4.7.2 

Выполнить миграции:
python3 manage.py migrate

Запустить проект:
python3 manage.py runserver

# Андрей, а эти команды выше обязательно писать? Я читала, что надо, но не поняла зачем, если это все стандарт?

Функционал API:
получать, создавать, удалять публикации;
получать информацию о сообществах, подписках, комментариях.

Например, POST-запрос с токеном Ириша - добавление нового поста.
POST .../api/v1/posts/

Пример ответа:
{
    "text": "буря небо мглою кроет",
    "group": 1
} 


