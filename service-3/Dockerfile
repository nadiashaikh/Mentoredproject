FROM python:3.7

RUN mkdir /opt/service-3

COPY . /service-3

WORKDIR /service-3

RUN pip install -r requirement.txt

ENTRYPOINT ["python", "app.py"]
