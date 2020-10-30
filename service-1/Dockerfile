FROM python:3.7

RUN mkdir /opt/service-1

COPY . /service-1

WORKDIR /service-1

RUN pip install -r requirements.txt

ENTRYPOINT ["python", "app.py"]
