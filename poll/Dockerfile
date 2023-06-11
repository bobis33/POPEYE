FROM python:3

WORKDIR /app

COPY . /app

EXPOSE 80

RUN pip install -r requirements.txt

CMD ["flask", "run", "--host0.0.0.0", "--port=80"]
