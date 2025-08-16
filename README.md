# for rasberry pi

docker-compose file 

....
  mysql:
    image: arm64v8/mysql
    container_name: mysql57
    restart: always
...

# login to mysql versi raspi
    + mysql -h 127.0.0.1 -P 3306 -u root -p

# login from network
    + login using HeidiSQL ver 12.11 minimum 
