# Project Name
Tomcat Application

#DESCRIPTION
containerizing a simple Tomcat web application and access the web page via SSL

#TABLE OF CONTENT
-Tomcat - Servlet/JSP container.
-Docker - tool designed to deploy and running applications.
-Elastic Search -  It allows you to store, search, and analyze big volumes of data quickly and in near real time. 
-Kibana - is a data visualization and exploration tool used for log and application monitoring use cases.

#INSTALL DOCKER/ON LINUX 
-ON LINUX TO INSTALL THE COMMANDS ON THE LOCAL MACHINE ARE 
    sudo apt install docker docker.io docker-composer

#USAGE
-After you install docker, use dockerhub to download tomcat image, by default tomcat will download the the latest version unless specified. command line is 
    docker pull tomcat
-Then check if there are any docker containers that are running.
    docker container ls
 note: if you want to stop the container
    docker kill
-Then run the the container .
    docker run -p 2000:8080
-You can see how the container works via web page 
DEPLOY THE SAMPLE.WAR FILE
-Downloaded the war file 
-save the the file in the directory to specify the file path
-run the image 


NOTE: if you are using docker compose there is no need to pull the images individually docker compose will manage that for you. 


 
