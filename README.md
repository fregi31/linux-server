﻿# linux-server NGINX
 apt install nginx
service nginx status / sudo systemctl start nginx
ufw allow 'Nginx Full'
ufw status
nano /var/www/html/index.nginx-debian.html

docker

sudo apt install apt-transport-https ca-certificates curl software-properties-common

GPG REPO:
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

APT REPO SOURCES:
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null


owncloud

wget https://raw.githubusercontent.com/owncloud/docs-server/master/modules/admin_manual/examples/installation/docker/docker-compose.yml

