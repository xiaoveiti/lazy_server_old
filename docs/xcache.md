# lazy_xcache
[lazy_server](https://github.com/gxf0/lazy_server/tree/master/README.md) :
 [lazy_deb](https://github.com/gxf0/lazy_server/tree/master/docs/deb.md) |
 [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md) |
 [lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md) |
 [lazy_secure](https://github.com/gxf0/lazy_server/tree/master/docs/secure.md) |
 [lazy_xcache](https://github.com/gxf0/lazy_server/tree/master/docs/xcache.md)
 * * *
 Install and configure APCu, OPCache and Redis.
 By deafualt, Redis will listen on a UNIX socket. Please use
 the command below, if it should listen to a TCP Socket instead.

### Usage

You can either clone the completely repo, or just download the scripts you need.

```
wget https://github.com/gxf0/lazy_server/blob/master/scripts/lazy_xcache
chmod +x lazy_xcahce
./lazy_xcache
```

### Optional Configure

You can define several variables at the beginning of the script.

```
php="7.2"
redis="true"
redis_tcp="false"
apcu="true"
opcache="true"
```

### Script Options

```
./lazy_secure <option>

 -t  --tcp      configure TCP Socket for Redis
 -s  --screen		show terminal output
 -x  --debug		debug (dev-debug.log)
 -h  --help		show this help
```

Examples:

Debug script :
```
 ./lazy_secure -x
 ./lazy_secure --debug
```

#### Author

* **Veit** - [gxf0](https://github.com/gxf0)

#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

#### Acknowledgments

* feel free to copy and adjust the scripts for your need
* feel free to improve the scripts - maybe you could also notice me - haha
* feel free to contact me, if you have any question
