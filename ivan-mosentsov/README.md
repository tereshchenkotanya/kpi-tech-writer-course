# Бот "Пошук лікаря"

## Опис додатку

Бот "Пошук лікаря" є додатком, який надає можливість пацієнтам отримати швидку консультацію від лікаря в скрутних умовах, коли вони не можуть звернутися до знайомого медичного працівника. Додаток також дає можливість лікарям з усього світу зареєструватися та допомогти пацієнтам у цей складний період.

## Технології

-   Python3 w/ Aiogram library
-   Python3 w/ Django for administration & database management
-   Postgresql & Redis

## Запуск

`$ git clone https://github.com/depozzyx/poshuk-likarya`

Додайте усі конфіги в .env

`$ python3 -m venv env`

`$ source env/bin/activate`

`$ pip install -r requirements.txt`

`$ python3 web/manage.py migrate`

Адмінка:

`$ python3 web/manage.py runserver 0.0.0.0:8000`

Бот:

`$ python3 bot/run.py`

## Підтримка проєкту

-   [Get me a coffee](https://get-me-a-coffee/depozzyx/)
-   Telegram: @depozzyx
