# cdn-aws-docker-lamp-wordpress-poc
The Proof of Concept of building amazing technology stack not paying a single dime.

So far so good:

- CloudFlare 
- AWS
- Docker
- Apache
- PHP

Effect: 
http://aws.dualhost.pl/ 

Manual configuration of DNS in CloudFlare needed.

Opening port 80 on AWS:
http://stackoverflow.com/questions/5004159/opening-port-80-ec2-amazon-web-services

Docker commands [WIP]:

    docker build -t wordpress .
    docker run -d -p 80:80 wordpress
    docker build -t tutum/mysql 5.6/
    docker run -d -p 3306:3306 tutum/mysql
