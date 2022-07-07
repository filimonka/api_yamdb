# api_yamdb
api_yamdb

Учебный командный проект в рамках курса Python-разработчик (Яндекс.Практикум)

Сервис, позволяющий оставлять отзывы на произведения, комментировать и общаться.
Доступ к сервису предосталяется по API.

## Основные эндпойнты (endpoints):

Регистрация пользователя:

```
api/v1/signup/ 
```
Получение токена для доступа к сервису:
```
api/v1/signup/ 
```
Доступ к жанрам, произведениям, отзывам (review) и комментариям:
```
api/v1/titles/
api/v1/genres/
api/v1/titles/<title_id>/reviews/
api/v1/titles/<title_id>/reviews/<review_id>/comments/
```

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/romankurortnyi/api_yamdb.git
```

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
. venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
cd yatube_api
```

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

_Authors:_

__Roman https://github.com/romankurortnyi__

__Dasha https://github.com/DashaPopovaDa__

__Kate https://github.com/filimonka__
