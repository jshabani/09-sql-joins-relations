1. fork and clone this repo
2. if `psql` isn't connecting, start your database server 
    - WIND: `pg_ctl -D 'C:/Program Files/PostgreSQL/9.6/data' start`
    - MAC: `pg_ctl -D /usr/local/var/postgres/ -l /usr/local/var/postgres/server.log start`
3. connect to `kilovolt` and `DROP TABLE`
4. set up your `conString`
5. start your node server!
6. do your assigned `TODO`