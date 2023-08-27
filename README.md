# docker

docker-compose up -d

web-interface:
<http://localhost:8000/>

PMA-interface:
<http://localhost:8080/>

cd apache-mysql-mongo

## run apache-php-mysql-mongodb stack
docker compose -f docker-compose-mongo.yml compose up -d

## run apache-php-mysql stack
docker compose up -d

## run mysql from cli
mysql -h 127.0.0.1 -P 3336 -u mop_admin -p

web-interface
<http://localhost:8080/>

PMA-interface:
<http://localhost:8085/>
### MYSQL_ROOT_PASSWORD: '<root-password>'