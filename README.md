# blogsite

basically we are launching a blogsite using automation.

### difference between Blogsite and Website :-

Blogs are a type of website.The only difference is that blogs have frequently updated content and websites tend to be much more static and is organized into pages. A blog can be a website on its own or a part of a bigger site. Early iteration of blogs were once used mostly for online personal journals.
    
learn to create your own site using automation.
## By using :-

-  LINUX 
    -  to use docker.Linux is the best-known and most-used open source operating system. As an operating system, Linux is software that sits underneath all of the other software on a computer, receiving requests from those programs and relaying these requests to the computer's hardware.
    
-  DOCKER
    -  Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package.
    
-  WORDPRESS
   -  Basically for framewaork. it uses PHP on background. On the surface Wordpress is a content management system. It is used by most of its users as a content management system and it offers all of the features of a content management system.
   
-  MYSQL
   -  we are using it for database management .MySQL Cluster enables users to meet the database challenges of next generation web, cloud, and communications services with uncompromising scalability.


## Requirements/Installation

Make sure you have the latest versions of `Docker` and `Docker Compose` installed on your machine.

### If Not than run the following commands:-

For Docker installation on linux[Ubuntu Distro/Similar commands for other distro as well]
 
    sudo apt-get update
    sudo apt-get remove docker docker-engine docker.io
    sudo apt install docker.io
    
After Docker installation Now install Docker Compose:-

    sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
    sudo chmod +x /usr/local/bin/docker-compose
    
After installation of the above files:-

    sudo systemctl start docker
    sudo systemctl enable docker


# Usage

Open a terminal and cd to the folder in which docker-compose.yml is saved and run:-

Hola!, Everything is Set now the containers are now built and running. You should be able to access the WordPress installation with the configured IP in the browser address by Enter your IP addrees of base os you also check by using `ifconfig` [http://XXX.XXX.XXX.XXX:8081]


# Here is an instance of my Blog site which I built using automation(in just single click):- 


![img1](https://user-images.githubusercontent.com/45136716/81509248-e3e99d80-9326-11ea-9257-bd6fb89a5dfa.jpg)


## Fore more reference on docker-compose:-

Start the containers with the up command in daemon mode (by adding -d as an argument) or by using the start command:

`docker-compose start`
    
Stopping containers

`docker-compose stop`


# AUTHOR
 
 [MANTHAN CHOUDHURY] (https://github.com/ManthanChoudhury)
 




