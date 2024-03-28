# nginx_server

## install nginx
### Ubuntu/Debian:

```
sudo apt update
sudo apt install nginx -y 
```
### centos/rhel
```
sudo yum update
sudo yum install nginx -y
```
### check status
```
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
sudo systemctl restart nginx
```
###  location of web page like apache2 /var/www/html in this server other location 

```
/usr/share/nginx/html/
```
### all configration file store in 
```
/etc/nginx/
```

### all log available i 
```
/var/log/nginx/
```





