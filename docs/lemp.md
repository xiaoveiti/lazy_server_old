# lazy_lemp

Setup and configure a fully functional LEMP stack, which includes:

* NGiNX (mainline)
* PHP 7.2 - FPM
  - GD, MySQL, CURL, OPcache, XML
  - ZIP, INTL, Mbstring, BZ2, DEV
* MariaDB 10.2 + phpmyAdmin (optional)

### Prerequisites

Don't forget to make the script executable.
```
chmod +x lazy_lemp
```

### Optional Configure

You can define several variables at the beginning of the script, but be sure
to also adjust the correspondingly source list.

```
php="7.2"
mariadb="10.2"

install_pma="true"
pma_dir="/var/www/phpmyadmin"
```

### Script Options

```
./lazy_lemp <option>

   -p  --password   specifiy mysql root password
   -n  --noadmin    don't install phpMyAdmin
   -s  --screen   show terminal output
   -x  --debug   (dev-debug.log)
   -h  --help   show this help
```

Examples:
```
   Debug script :
   ./lazy_lemp -x
   ./lazy_lemp --debug

   Specify an MySQL root Password:
   ./lazy_lemp -p<your password>
   ./lazy_lemp -password<your password>
```
