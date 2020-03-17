jenkinsOnDocker
to run jenkins master and jenkins node
run:
 docker-compose -f docker-compose.ci.yml up


Find the url for jenkins in the ip of the vm with the command:
docker-machine ip default

And navigate to jenkins web with the url:
http://192.168.99.100:8080/
