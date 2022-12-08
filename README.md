# django-docker steps

- sudo systemctl start docker
- sudo docker-compose run web django-admin startproject mysite .
- sudo chown -R $USER:$USER
- docker-compose up

- docker exec lab_web_1 python manage.py startapp greet
or

- [annu@fedora lab]$ docker exec -it lab_web_1 /bin/bash
root@5b32f05e4be8:/app# python manage.py startapp hello
