# flaskDocker
Dockerize your flask application

1)Docker Image build command :-
  docker build -t flask-docker:latest .
  
2)After successfully building the image
   docker run -d -p 5000:5000 flask-docker
