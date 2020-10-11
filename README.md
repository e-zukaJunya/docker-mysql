docker-compose up -d
docker-compose exec mysql bash
docker-compose down --rmi all -v

# MySQL を起動

mysql -u root -p -h 127.0.0.1
