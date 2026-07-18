# Commands Used

## Update Ubuntu
sudo apt update
sudo apt upgrade -y

## Install Nginx
sudo apt install nginx -y

## Manage Nginx
sudo systemctl status nginx
sudo systemctl start nginx
sudo systemctl restart nginx
sudo systemctl enable nginx

## Test Configuration
sudo nginx -t

## Check IP Address
hostname -I

## Run Backend
node app.js