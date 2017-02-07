# Linux-WebServer

* IP Address: 52.35.58.113

* SSH Port: 2200

* URL: http://ec2-52-35-58-113.us-west-2.compute.amazonaws.com/

# Software Installed:

* apache2
* postgresql
* libapache2-mod-wsgi

# Changes:

* configured firewall to allow incoming requests on port 2200(ssh), 80(http), 123(NTP),
* created a postgresql role called catalog with limited privileges,
* can't ssh to root

# Resources used to complete the project:

* DigitalOcean tutorials: [How To Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps), 
* [How To Setup a Firewall with UFW on an Ubuntu and Debian Cloud Server](https://www.digitalocean.com/community/tutorials/how-to-setup-a-firewall-with-ufw-on-an-ubuntu-and-debian-cloud-server),
* [How To Edit the Sudoers File on Ubuntu and CentOS](https://www.digitalocean.com/community/tutorials/how-to-edit-the-sudoers-file-on-ubuntu-and-centos)
