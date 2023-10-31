1. cd container
2. docker-compose build
3. docker-compose volume create mysqldata
3. docker-compose -p node-container up -d
4. buka notepad run as admin lalu tambahkan 127.0.0.1 node.local di C:/Windows/System32/drivers/etc/hosts
5. docker exec -ti node bash
6. npx sequelize-cli db:migrate
