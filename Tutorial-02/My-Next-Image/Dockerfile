FROM python:3.10-alpine

WORKDIR /app

RUN apk update

COPY requirements.txt requirements.txt
COPY app.py app.py

RUN pip install -r requirements.txt

CMD ["python", "app.py"]