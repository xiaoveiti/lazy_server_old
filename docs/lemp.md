# lazy_lemp
[lazy_server](https://github.com/gxf0/lazy_server/tree/master/README.md) :
 [lazy_deb](https://github.com/gxf0/lazy_server/tree/master/docs/deb.md) |
 [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md) |
 [lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md) |
 [lazy_pi](https://github.com/gxf0/lazy_server/tree/master/docs/pi.md) |
 [lazy_secure](https://github.com/gxf0/lazy_server/tree/master/docs/secure.md) |
 [lazy_ts](https://github.com/gxf0/lazy_server/tree/master/docs/ts3.md)
 
Setup and configure a fully functional LEMP stack, which includes:

* NGiNX ([lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md))
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
  -s  --screen     show terminal output
  -x  --debug      (dev-debug.log)
  -h  --help       show this help
```

Examples:

Debug script :
```
 ./lazy_lemp -x
 ./lazy_lemp --debug
```

Specify an MySQL root Password:
```
 ./lazy_lemp -p<your password>
 ./lazy_lemp -password<your password>
```

#### Author

* **Veit** - [gxf0](https://github.com/gxf0)

#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

#### Acknowledgments

* feel free to copy and adjust the scripts for your need
* feel free to improve the scripts - maybe you could also notice me - haha
* feel free to contact me, if you have any question
