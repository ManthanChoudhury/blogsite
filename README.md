# Blogsite

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
   -  Basically for framework. it uses PHP on background. On the surface Wordpress is a content management system. It is used by most of its users as a content management system and it offers all of the features of a content management system.
   
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

-  Start the containers with the up command in daemon mode (by adding -d as an argument) or by using the start command:

       docker-compose start
    
-  Stopping containers

       docker-compose stop

# SETUP
  -  when it get enabled. (lot of stuff going on background like setup of php, mysql, porting, data storing)
  
![sc 1](https://user-images.githubusercontent.com/45136716/81510374-cfa99e80-932e-11ea-9563-d09f31a86657.png)


  -  `ifconfig`:- Get your IP address  [http://XXX.XXX.XXX.XXX:8081] using this on google chrome we will GUI from it. 
  
  
![project1](https://user-images.githubusercontent.com/45136716/81510381-d7694300-932e-11ea-8093-d0914dad86b4.jpg)


  -  it takes some initial setup (password , email id, heading)    
  
  
![project2](https://user-images.githubusercontent.com/45136716/81510383-db956080-932e-11ea-87fd-9adef694f1de.jpg)


  -  it takes your id and password
  
  
![project 3](https://user-images.githubusercontent.com/45136716/81510388-e3ed9b80-932e-11ea-9eef-31653c6132a9.jpg)


  -  Ready to go..(create your first BLOG)
  
  
![project 4](https://user-images.githubusercontent.com/45136716/81510390-f7006b80-932e-11ea-93cb-6f6a347ce805.jpg)


  -  loading data from blog site (MEANS DATA IS PERMANENT)  
  
  
![sc 2](https://user-images.githubusercontent.com/45136716/81510393-fbc51f80-932e-11ea-843c-c21db6d49ba3.png)




# AUTHOR
 
 [MANTHAN CHOUDHURY] (https://github.com/ManthanChoudhury)
 
 
 
 




