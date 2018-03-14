# lazy_pi
[lazy_server](https://github.com/gxf0/lazy_server/tree/master/README.md) :
 [lazy_deb](https://github.com/gxf0/lazy_server/tree/master/docs/deb.md) |
 [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md) |
 [lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md) |
 [lazy_pi](https://github.com/gxf0/lazy_server/tree/master/docs/pi.md) |
 [lazy_secure](https://github.com/gxf0/lazy_server/tree/master/docs/secure.md) |
 [lazy_ts](https://github.com/gxf0/lazy_server/tree/master/docs/ts3.md)
 * * *
Simple update Pi-hole and your Block-List.
If Pi-hole is not installed, the script will install it for you.

You could also just use the original pihole script, to update your system, but this will not work, 
if you changed the webdir for the admin webinterface. So I implemented this small update function.

### Usage

You can either clone the completely repo, or just download the scripts you need.

```
wget https://github.com/gxf0/lazy_server/blob/master/scripts/lazy_pi
chmod +x lazy_pi
./lazy_pi
```

### Optional Configure

You can define several variables at the beginning of the script.

```
pi_dir="/opt/pihole"
pi_webdir="/var/www/xf0/pihole"
```

### Script Options

```
./lazy_pi <option>

 -u  --update   update/install pi-hole
 -l  --list     update lists
 -s  --screen		show terminal output
 -x  --debug		debug (dev-debug.log)
 -h  --help		  show this help
```

Examples:

Debug script :
```
 ./lazy_pi -x
 ./lazy_pi --debug
```

#### Author

* **Veit** - [gxf0](https://github.com/gxf0)

#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

#### Acknowledgments

* feel free to copy and adjust the scripts for your need
* feel free to improve the scripts - maybe you could also notice me - haha
* feel free to contact me, if you have any question
