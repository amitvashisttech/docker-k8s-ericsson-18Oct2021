# Base Image 
FROM ubuntu:16.04 

# Owner of Image 
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update the Apt Repo.
RUN apt-get update

# Install Apache Packages
RUN apt-get install apache2 -y

# Custom Web Page 
COPY index.html /var/www/html/

# Expose 
EXPOSE 80 
EXPOSE 3306 

# Excute the App. 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
