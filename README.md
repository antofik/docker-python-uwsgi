# docker-python-uwsgi
Base image for django+uwsgi+nginx

Launched wsgi.py via supervisor. Exposes /tmp/uwsgi.sock

Example:

  docker build -t antofik/test .
  docker run -v ~/test:/tmp antofik/test 
  docker run -v ~/test:/tmp nginx
  
