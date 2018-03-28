# lazy_secure
[lazy_server](https://github.com/gxf0/lazy_server/tree/master/README.md) :
 [lazy_deb](https://github.com/gxf0/lazy_server/tree/master/docs/deb.md) |
 [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md) |
 [lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md) |
 [lazy_secure](https://github.com/gxf0/lazy_server/tree/master/docs/secure.md) |
 [lazy_xcache](https://github.com/gxf0/lazy_server/tree/master/docs/xcache.md)
 * * *
Secure your Server:
 - install and configure fail2ban, apticron & rkhunter
 - change ssh port

### Usage

You can either clone the completely repo, or just download the scripts you need.

```
wget https://github.com/gxf0/lazy_server/blob/master/scripts/lazy_secure
chmod +x lazy_secure
./lazy_secure
```

### Optional Configure

You can define several variables at the beginning of the script.

```
fail2ban="true"
apticron="true"
rkhunter="true"
```

### Script Options

```
./lazy_secure <option>

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
