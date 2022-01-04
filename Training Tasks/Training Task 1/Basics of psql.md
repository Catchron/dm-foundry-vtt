Run the psql command line interface:<br>
``sudo -u postgres psql``<br>

List databases:<br>
``\l``<br>

List users and permissions:<br>
``\du``<br>

Get info about current connection:<br>
``\conninfo``<br>

To change user:<br>
``\c - [user]``<br>
* "-" substitutes for the current database.<br>

To change database and user:<br>
``\c a_new_database a_new_user``<br>

Creating user:<br>
``sudo -u postgres createuser <username>``<br>
or
``CREATE USER [username] WITH PASSWORD '[password]';``<br>

Giving the user a password:<br>
``psql=# alter user [username] with encrypted password '[password]';``<br>
or<br>
``ALTER USER [username] WITH PASSWORD '[password]';``<br>

Giving user privligaes:<br>
ALTER USER [username] WITH SUPERUSER;<br>

Granting privileges on database:<br>
``psql=# grant all privileges on database <dbname> to <username> ;``<br>

Creating Database:<br>
``sudo -u postgres createdb [dbname]``<br>
