virtuabbox 192.168.99.100
docker run --name cmysql -e MYSQL_ROOT_PASSWORD=admin -d mysql
docker exec -ti {id} bash