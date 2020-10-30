FROM python: 3.7

RUN mkdir /opt/service-4

COPY . /service-4

WORKDIR /service-4

RUN pip install -r requirements.txt

ENTRYPOINT ["python", "app.py"]
