# Udacity Linux Server Configuration Project

The Server Deployed on [http://ec2-18-220-176-206.us-east-2.compute.amazonaws.com](http://ec2-18-220-176-206.us-east-2.compute.amazonaws.com)  `IP : 18.220.176.206`

## Connection Settings
* IP : 18.220.176.206`
* SSH Port : 2200
* HTTP : 80
* NLT Port : 123


## Installed Software
* Apache
* Python
* WSGI `libapache2-mod-wsgi`
* PostgreSQL Server
* pip
* Flask
* virtualenv

## Configurations Summary 

* Created a user named `grader` given `sudo` access.
* Configured `UFW` Firewall to Only allow connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
* Key-based SSH authentication is enforced.
* All system packages have been updated to most recent versions.
* SSH is hosted on non-default port (port 2200)
* Configured Apache Web Server Up and running on port 80.
* Configured PostgreSQL to serve data.
* Apache Web server has been configured to serve the  [Item Catalog application](http://ec2-18-220-176-206.us-east-2.compute.amazonaws.com) as a WSGI app.

## Resources
* [How To Set Up a Firewall with UFW on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu-16-04)
* [How To Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)





