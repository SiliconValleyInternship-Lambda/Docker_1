# docker-demo
A docker compose example that provides a Nginx, Flask, and React container

# How to use a docker and composer
---
## Docker Prerequisites:
- Windows
https://docs.docker.com/docker-for-windows/install/
- Mac
https://docs.docker.com/docker-for-mac/install/

Refer to
```
git clone git@github.com:shpark76/docker-demo.git
```


### 1. git clone
```
git clone git@github.com:SiliconValleyInternship-Lambda/Docker_1.git
```

### 2. docker compose build and up 
```
$ docker compose build
```

# Let’s run the API using docker
## Let’s build the docker image
```
docker compose build
```

## Docker compose up with all associated docker compose services
```
$ docker compose up
```
#### Note:
If you prefer to use a daemon mode, Let’s run the above command in the background:
```
$ docker compose up -d
```

### 3. Flask Python application
```
http://localhost:5000
```

### 4. React application
```
...
http://localhost:3000
```  

### 5. Nginx application
Frontend
```
...
http://localhost:80
```  
Backend
```
...
http://localhost:8000
```  

#### If you want to build/run a specific application
> ```
> docker compose build <custom service>
> docker compose run <custom service>
> 
> i.e. 
> docker compose build nodejs_app
> docker compose run nodejs_app
> ```
