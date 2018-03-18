# lazy_ngx
[lazy_server](https://github.com/gxf0/lazy_server/tree/master/README.md) :
 [lazy_deb](https://github.com/gxf0/lazy_server/tree/master/docs/deb.md) |
 [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md) |
 [lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md) |
 [lazy_secure](https://github.com/gxf0/lazy_server/tree/master/docs/secure.md)
* * *
Build NGiNX from Source, include [cache_purge plugin](https://github.com/FRiCKLE/ngx_cache_purge). This script is part of [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md), but also can be used to just build NGiNX,
without PHP and MariaDB, as a standalone http proxy.

This script will check, if NGiNX is already installed and just update/rebuild NGiNX from source. So keep and use this script, if you want to keep your NGiNX Setting up-to-date.

### Usage

You can either clone the completely repo, or just download the scripts you need.

```
wget https://github.com/gxf0/lazy_server/blob/master/scripts/lazy_ngx
chmod +x lazy_ngx
./lazy_ngx
```

### Script Options

```
./lazy_ngx <option>

  -s  --screen  show terminal output
  -x  --debug   debug (dev-debug.log)
  -h  --help    show this help
```

Examples:

Debug script :
```
 ./lazy_ngx -x
 ./lazy_ngx --debug
```

#### Author

* **Veit** - [gxf0](https://github.com/gxf0)

#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

#### Acknowledgments

* feel free to copy and adjust the scripts for your need
* feel free to improve the scripts - maybe you could also notice me - haha
* feel free to contact me, if you have any question
