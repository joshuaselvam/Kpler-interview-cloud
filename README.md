- Launched a test app called started written in node js
-  adonis framework

  "name": "starter-app",
  "version": "4.1.0",
  "adonis-version": "4.1.0",
  "description": "The Starter application",
  "main": "index.js",
 
 - used Elastic Beanstalk to launch it in a multicontainer environment

- To look into: 

-     Dockerfile-socar  - docker file for creating image
-     Dockerrun.aws.json - multicontainer - images used nodejs/nginx
-     Dockerfile-nginx  - for nginx reverse proxy 
-     nginx.conf - nginx configuration

Infrastructure as a code:

ebs-terraform -   Elastic Beanstalk Cluster / 
rds-terraform -   RDS - postgress DB  / 
vpc-terraform -   VPC - modules



