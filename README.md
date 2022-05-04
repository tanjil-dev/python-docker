# djangobackend

### virtualenv install
```
pip3 install virtualenv
```

### create virtual environment
```
python -m virtualenv [name]
```

### activate virtual environment
```
source /[name]/bin/activate
```

### intall all requirements
```
pip3 install -r requirements.txt
```

### docker image
```
docker build --tagg [docker-name]
```

### stop docker image
```
docker stop [docker-name]
```

### mysql config
```
docker volume create mysql
docker volume create mysql_config
docker network create mysqlnet
```
### stop mysql service
```
sudo service mysql stop
```

### docker compose
```
docker compose -f docker-compose.dev.yml up --build
```
