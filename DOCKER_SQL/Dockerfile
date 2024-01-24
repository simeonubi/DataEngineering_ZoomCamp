FROM python:3.9.1

RUN apt-get install wget
Run pip install pandas sqlalchemy psycopg2

WORKDIR /app
COPY ingest_data.py ingest_data.py

ENTRRYPOINT [ 'python']