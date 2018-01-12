# up6-linux-configuration
## Udacity FSND Project Linux Server Configuration  ##
This project is connected to the _Full Stack Web Developer Nanodegree Program_ course by **Udacity**.
It contains a baseline installation of a Linux distribution on a virtual machine and to prepare it hosting as a web applications. It includes installing updates, securing the machine agains a number of attack vectors and installing/configuring web and database servers.
## Install ##
Created GitHub repository for this project.
https://github.com/nacikaly17/up6-linux-configuration
### The IP address and SSH port so the server ###
```
    IP Address: 165.227.136.243
    SSH Port : 2200
```
### The URL to hosted web application ### 
```
    http://165.227.136.243/
```
### A list of  third-party resources ### 
* PostgreSQL
* Python2.7
* Flask
* Apache2

###  A summary of software installed ### 

*   Get Linux Server Instance server.
```
Require a Ubuntu Linux Server Instance from DigitalOcean
```
* Secure server
```
Change root user password
Create a new  user grader ( project reviewer ) and secure user access
Change the SSH port from 22 to 2200
Activate SSH access 
Configure the Uncomplicated Firewall (UFW)
Enable UFW
Deactivate remote login  for root
```

* Update and Install Software.
```
Update all currently installed packages.
```
* Prepare to deploy project.
```
  Install python2.7.
  Install apache2
  Install and configure PostgreSQL
```
* Deploy the Item Catalog project.
```
 Clone and setup your Item Catalog project from the Github repository you created earlier in this Nanodegree program.
Github address for my “Item Catalog”  ( project 4 ) is:
https://github.com/nacikaly17/nk-catalog.git
```
### Summary of configurations ###
```
 Configure apache2 web server to run nk-catalog as wsgi application 
 Run python init_catalog.py to create an initial catalog.db 
 Making  .git directory as not publicly accessible via a browser
```
