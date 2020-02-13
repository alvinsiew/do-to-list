# do-to-list

This is a backend for todolist. Still in progress.

# How to create mysql for to-do-list backend

```bash
docker pull mysql:latest
docker run -d -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=root mysql
docker exec -it mysql mysql -uroot -proot -e 'CREATE DATABASE todolist'
```

# How to connect to database

```bash
docker exec -ti mysql mysql -uroot -proot
```
