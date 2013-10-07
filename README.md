docker-jenkins
==============

Dockerfile to build jenkins container

**Build**

`sudo docker build -t jonhadfield/jenkins github.com/jonhadfield/docker-jenkins`

**Run**

`JENKINS_ID=$(sudo docker run -d jonhadfield/jenkins)`

**Connect**
http://localhost:8080/

Docker will attempt to expose jenkins on local port 8080.
You can run this to confirm the local port:
`sudo docker port $JENKINS_ID 8080`
