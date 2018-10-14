# dockerMysql

## docker run 

docker run --name mysqlTest -d -p 3306:3306 --env="MYSQL_DATABASE=test" --env="MYSQL_ROOT_PASSWORD=Qwerty@321" --env="MYSQL_USER=datreon"--env="MYSQL_PASSWORD=Qwerty@321" mysql:5.7 --bind_address=0.0.0.0
