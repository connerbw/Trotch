Trotch
======

_We guarantee results marginally better than random™_

### INSTALL ###

 1. `./composer.phar install`

 2. Import `./config/sql/db-mysql.sql` into MySQL (todo)

 3. `chmod 777 ./logs`
    `chmod 777 ./tmp`

 4. `mv ./config/sample-config.php ./config/config.php`
    `mv ./public/sample-.htaccess ./public/.htaccess`

 5. Edit `./config.php` and `./public/.htaccess` accordingly

 6. Point your virtual host document root to `./public/`