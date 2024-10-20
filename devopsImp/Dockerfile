FROM python:3.8-slim-buster

WORKDIR /app

RUN pip install django psycopg2-binary

COPY . .

EXPOSE 8000

CMD python manage.py runserver