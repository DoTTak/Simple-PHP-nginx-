# PHP with Docker(PHP+Nginx)

## Get Started

### 1. Image Build
```
docker build -t php-nginx:0.1 .
```

### 2. Image Build
```
docker run -d -p 8080:8080 -v ./src:/var/www/html --name php-nginx php-nginx:0.1
```