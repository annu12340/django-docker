# django-docker steps

- sudo systemctl start docker
- sudo docker-compose run web django-admin startproject mysite .
- sudo chown -R $USER:$USER
- docker-compose up
