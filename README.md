<h1 align="center">
Bitnet IO Nodes Map
<br><br>
<br><br>
</h1>

fix using phpmyadmin

php /var/www/html/nodes/cron.php

Uncaught PDOException: SQLSTATE[HY000]: General error: 1364

![s1](stack.imgur.com/26DXU.png)

![s1](https://github.com/bitnet-io/Bitnet-Nodes-Map/releases/download/fix-phpmyadmin-mysql-flags/26DXU.png)



## How to Install 💻

# requires php 8.3 and apache2 with mariadb-server

1- Get an Hosting  Account tor Web Server that supports ```PHP (V. 7 =>)``` + ```MySQL/MariaDB``` (also works locally with Docker or Xampp for exemple)

2- Create an Data Base and import the file ```nodes.sql```

3- Get create an account on ipinfo.io and generate a token.

4- Open the file with any text editor ```inc/config.php``` and follow the configurations needed

5- Upload all files (excluding nodes.sql and readme.md) to your Hosting Account

6- Add a cron task to the file cron.php, and let it run every minute and enjoy it :)

###Notes:

- It dosent store the Dogecoin Node IP on the Map Database. The GPS coordinates are taken from the Internet Service provider registration address and not from the node IP home address.
