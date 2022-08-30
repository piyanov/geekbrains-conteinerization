FROM python:3.9

WORKDIR /app

COPY ./python/ .
RUN pip install -r requirements.txt

EXPOSE 8080

ENTRYPOINT python ./app.py
