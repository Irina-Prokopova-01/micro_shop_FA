# micro_shop_FA

## Описание проекта

### Функциональные возможности
Модели данных:


### API:


### Тестирование:


### Технологии
* Язык программирования: 
  Python 3.12+
* Фреймворки:
  FastAPI
* База данных: PostgreSQL 15+
* Дополнительно:
  SQLAlchemy 
  alembic
  httpx = "^0.28.1"
  uvicorn = {extras = ["standard"], version = "^0.34.3"}
  python-multipart = "^0.0.20"
  sqlalchemy = "^2.0.41"
  alembic = "^1.16.1"
  python-slugify = "^8.0.4"
  asyncpg = "^0.30.0"
  python-dotenv = "^1.1.0"


### Инструкция по запуску проекта
* Клонирование репозитория
 git clone https://github.com/Irina-Prokopova-01/micro_shop_FA
* Установка зависимостей
 для pip: pip install -r requirements.txt
 для poetry: poetry install
* Запуск проекта
 uvicorn app.main:app --port 8000 --reload
* Доступ к документации API
  http://127.0.0.1:8000/docs#/