FROM python:3.7	

RUN mkdir /opt/service-2

Copy . /service-2

WORKDIR /service-2

RUN pip instal -r requirements.txt

ENTRYPOINT ["python", "app.py"]
