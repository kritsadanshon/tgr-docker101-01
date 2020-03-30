sudo docker build -t kritsadanshon/mywebsite:v1 ubuntu

sudo docker run -d -p 83:80 kritsadanshon/mywebsite:v1

sudo docker build -t kritsadanshon/mywebsite:v2 nginx

sudo docker run -d -p 84:80 kritsadanshon/mywebsite:v2
