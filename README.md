Aura Bundle
=======

Aura Bundle is a combination of software and file replacements for [Aura](https://github.com/aura-project/aura),
giving it the ability to run without additional setups (aside
from compiling). It includes a portable MySQL server (MariaDB),
a database management software (HeidiSQL), and soon a web server.

Usage
---------
Download Aura, compile it, drop in Bundle, done!

Aura can be started as usual, with the start-server.bat. Unlike before,
the database server will start first, followed by Login and Channel.

Notes
---------
* Don't replace the Bundle files! By doing so you'd basically wipe all your character data, since the database is stored in a sub-folder.
* For security reasons this should only be used in test servers.

Used Software
---------
* MariaDB 5.5.36 - http://mariadb.org/
* HeidiSQL 8.3 - http://www.heidisql.com/
