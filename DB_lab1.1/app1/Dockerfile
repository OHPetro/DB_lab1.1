FROM python:3.10.7-slim-buster

WORKDIR /app1

RUN pip install --upgrade pip
COPY requirements.txt ./requirements.txt
RUN pip install -r requirements.txt
#RUN apt-get update && apt-get install -y libpq-dev

COPY . .


CMD ["python", "main.py"]
