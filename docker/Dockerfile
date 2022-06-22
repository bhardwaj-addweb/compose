FROM ubuntu:latest
LABEL name=bhardwaj
RUN apt update &&  apt install -y nginx && service nginx start && apt-get install -y mysql-client mysql-server && apt-get install -y php libapache2-mod-php php-mysql php-curl php-gd php-mbstring php-xml php-xmlrpc php-soap php-intl php-zip
#ADD http://wordpress.org/latest.tar.gz
#CMD tar -xzvf latest.tar.gz
