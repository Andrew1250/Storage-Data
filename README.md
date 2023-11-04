1. cd container
2. docker-compose build
3. docker-compose volume create mysqldata
4. docker-compose -p web up -d
5. buka notepad run as admin lalu tambahkan 127.0.0.1 node.local di C:/Windows/System32/drivers/etc/hosts
6. docker exec -ti node bash
7. npx sequelize-cli db:migrate
