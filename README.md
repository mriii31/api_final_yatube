# api_final

### Описание:

REST API для социальной сети YaTube
Приложение для публикации постов c картинками. Посты можно комментировать и определять в группы. На понравившихся авторов можно подписываться.


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```http
git clone https://github.com/mriii31/api_final_yatube
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```http
python3 -m venv env
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```http
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполнить миграции:

```http
python3 manage.py migrate
```

Запустить проект:

```http
python3 manage.py runserver
```
