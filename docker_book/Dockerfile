FROM python:3.11-bookworm

ENV APP_HOME /app

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

CMD ["python", "app.py"]
