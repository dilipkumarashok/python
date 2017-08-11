FROM python:latest

WORKDIR /usr/src/app

ADD . /usr/src/app

RUN pip install -r requirements.txt

EXPOSE 80

ENV NAME myapp

CMD ["python", "flask1.py"]
