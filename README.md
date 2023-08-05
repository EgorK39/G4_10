1. git clone git@github.com:EgorK39/G4_10.git
2. cd G4_10/
3. sudo service docker start
4. sudo service postgresql start
5. sudo -u postgres psql
6. CREATE DATABASE docker_test
7. <h3>В файле .env.dev в SQL_PASSWORD нужно подставить свой пароль от postgres и в файле .env.db в POSTGRES_PASSWORD нужно подставить тоже пароль от postgres, иначе ничего работать не будет.</h3>
Например, SQL_PASSWORD=asd123 и POSTGRES_PASSWORD= asd123

8. docker-compose up -d --build
9. http://localhost:8080/admin/
10. Данные для входа в админку:
11. Username: admin 
12. Password: qwerty

