<h3>A simple Web API with Node and MySQL</h3>

1. Start MySQL.
2. Create MySQL DB with name `testdb`.
3. Create table `customers` with following command: <br />
      `CREATE TABLE IF NOT EXISTS customers (` <br />
      `   id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,` <br />
      `    email varchar(255) NOT NULL,` <br />
      `   name varchar(255) NOT NULL,` <br />
      `    active BOOLEAN DEFAULT false` <br />
      `) ENGINE=InnoDB DEFAULT CHARSET=utf8;`
4. Run app.js via `node app.js` command.