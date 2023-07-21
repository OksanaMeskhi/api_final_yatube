## api final

Проект Yatube - это социальная сеть, где можно вести свой дневник, постить котиков(но это не точно), подписываться на понравившихся авторов, комментировать их посты и создавать тематические группы.

Стек технологий
Python 3.9.10,
Django 3.2.16,
DRF,
JWT

Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

`git clone git@github.com:OksanaMeskhi/api_final_yatube.git
cd yatube_api`

Создать и активировать виртуальное окружение:

`python3 -m venv venv
Если у вас Linux/macOS
source venv/bin/activate
Если у вас windows
source venv/scripts/activate`

Установить зависимости из файла requirements.txt:

pip install -r requirements.txt
Установить Djoser

Выполнить миграции:

`python3 manage.py migrate`

Запустить проект:

`python3 manage.py runserver`

Автор:
@OksanaMeskhi
