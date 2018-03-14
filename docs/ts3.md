# lazy_ts
[lazy_server](https://github.com/gxf0/lazy_server/tree/master/README.md) :
 [lazy_deb](https://github.com/gxf0/lazy_server/tree/master/docs/deb.md) |
 [lazy_lemp](https://github.com/gxf0/lazy_server/tree/master/docs/lemp.md) |
 [lazy_ngx](https://github.com/gxf0/lazy_server/tree/master/docs/ngx.md) |
 [lazy_pi](https://github.com/gxf0/lazy_server/tree/master/docs/pi.md) |
 [lazy_secure](https://github.com/gxf0/lazy_server/tree/master/docs/secure.md) |
 [lazy_ts](https://github.com/gxf0/lazy_server/tree/master/docs/ts3.md)
 * * *
A simple script to deploy a TeamSpeak 3 Server on your machine. At least I dislike to copy stuff from the shell, but you need the Server Query Login, or the Admin Token, so all this information, include your server public IP will be stored in a txt file (ts3_login.txt). Still to lazy to check the dir? Or maybe you just want to set up the server for some of your friends and not really mind, what they are going to do with it? You also could automatically send the login information to your/their email.

If you don't need this server to be up the whole time, and just want to set up for testing, or maybe for some event, you can also use this script to destroy/delete the server include all files.

### Usage

You can either clone the completely repo, or just download the scripts you need.

```
wget https://github.com/gxf0/lazy_server/blob/master/scripts/lazy_ts
chmod +x lazy_ts
./lazy_ts
```

### Optional Configure

You can define several variables at the beginning of the script, but be sure
to also adjust the correspondingly tar command, if you change the file.tar.bz2.

```
ts_user="teamspeak"  
ts_dir="/opt/teamspeak"  

ts_download="http://dl.4players.de/ts/releases/3.1.0/teamspeak3-server_linux_amd64-3.1.0.tar.bz2"

serverip=$(ip route get 8.8.8.8 | awk 'NR==1 {print $NF}')
ts_mail="false" # by default no mail will be send
```

### Script Options

```
./lazy_ts <option>

  -e  --email     specify email to receive login
  -k  --kill      delete server include all files
  -s  --screen	  show terminal output
  -x  --debug		  debug (dev-debug.log)
  -h  --help		  show this help
```

Examples:

Specify email :
```
 ./lazy_ts -m<mail@domain.tld>
 ./lazy_ts --mail<mail@domain.tld>
```

### Manage Teamspeak 3 Server
```
ts3 <start|stop|restart|status>
```

#### Author

* **Veit** - [gxf0](https://github.com/gxf0)

#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

#### Acknowledgments

* feel free to copy and adjust the scripts for your need
* feel free to improve the scripts - maybe you could also notice me - haha
* feel free to contact me, if you have any question
