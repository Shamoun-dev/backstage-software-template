FROM python:3.10-alpine

COPY ./requirments.txt .

RUN pip install -r ./requirments.txt

COPY ./src /app

CMD python /app/app.py