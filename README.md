### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

git clone https://github.com/yandex-praktikum/...

cd kittygram2plus

Cоздать и активировать виртуальное окружение:

python3 -m venv env

source env/bin/activate

python3 -m pip install --upgrade pip

Установить зависимости из файла requirements.txt:
pip install -r requirements.txt

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
    "text": "а Клара у Карла украла кларнет",
    "group": 1
} 


