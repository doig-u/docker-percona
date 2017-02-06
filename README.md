# Ubuntu LTS based Percona Server

Build based on Dockerfile from https://hub.docker.com/_/percona/ only for Ubuntu LTS.

Run: `$ docker run -p 3306:3306 --name mysql -e "MYSQL_ALLOW_EMPTY_PASSWORD=1" doigu/percona`

Check: `$ mysql -uroot -h127.0.0.1 -P3306`