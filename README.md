<h1>Party Parrot App</h1>

<img src='media/images/party-parrot.gif' alt='parrot' height="200" width="200">
<br>
<br>
<h3></h3>

Sample Python application on Django with PostgreSQL database.

<h3>Requirements</h3>

____


<<<<<<< HEAD
- docker 27.3.1
=======
- django 4.0.1
- Pillow 9.0.0
- psycopg2-binary 2.9.3
- django-prometheus 2.2.0
>>>>>>> 7a32ca10ff2604db537b09f54e59bbfbf49ae8cc

<h3>Deployment</h3>

____


<<<<<<< HEAD
* start application:
```shell
docker compose up
=======

- install Python 3.8
- install libs 
```shell
      pip3 install -r requirements.txt
```

* Set environment export for variables:
```yaml
      DJANGO_DB_HOST: db
      DJANGO_DB_NAME: app
      DJANGO_DB_USER: worker
      DJANGO_DB_PASS: worker
      DJANGO_DB_PORT: "5432"
      DJANGO_DEBUG: "False"
```


* migrate database:
```shell
python3 manage.py migrate
```

* start application:
```shell
python3 manage.py runserver 0.0.0.0:8000
>>>>>>> 7a32ca10ff2604db537b09f54e59bbfbf49ae8cc
```
