## A simple NodeJS and MySQL API
#### Steps to be followed :
- Configure database properties from `/config/db`
- Start MySQL
- Create database __testdb__.
- Create table `customers` by following SQL command :
```
CREATE TABLE IF NOT EXISTS `customers` (
    id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
    email varchar(255) NOT NULL,
    name varchar(255) NOT NULL,
    active BOOLEAN DEFAULT false
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```
- Run `node app`
