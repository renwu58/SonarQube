# SonarQube
SonarQube Docker Container
Original: https://hub.docker.com/_/sonarqube/

Creates a docker container with SonarQube, incl. several plugins Since the original Dockerfile does not support plugins, I had to extend the Dockerfile
  
Usage:
```
$ docker build -t sonar .
$ docker run -d -p 8800:9000 sonar
```
More see original document
