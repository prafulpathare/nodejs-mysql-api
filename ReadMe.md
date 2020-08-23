## A simple NodeJS and MySQL API
#### Steps before deploying
- Configure database properties from `/config/db`
- Start MySQL server
- Create database __testdb__.
- Create table `customers` by following SQL command :
```sql
CREATE TABLE IF NOT EXISTS `customers` (
    id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
    email varchar(255) NOT NULL,
    name varchar(255) NOT NULL,
    active BOOLEAN DEFAULT false
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```
- Run
    ```sh
    $ node app
    ```
