# sql-injection-php

php・mysqlの環境を想定しています。

## テーブルを作成する

データベースに入って、SQL文でテーブルを作成します。

```
CREATE TABLE contents (
    id INT(11) AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(191),
    content VARCHAR(191),
    posted_at DATETIME
) engine=innodb default charset=utf8
```

```
CREATE TABLE users (
    id INT(11) AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(191),
    tel Int(11),
    address VARCHAR(191)
) engine=innodb default charset=utf8
```
