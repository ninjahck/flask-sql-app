FROM python:3.7-alpine

EXPOSE 5000

WORKDIR /app

COPY requirements.txt /app
RUN pip3 install -r requirements.txt
COPY static /app/static
COPY templates /app/templates
COPY app.py /app
CMD python3 app.py