# lazy_secure

Update Pi-hole and your Block-List.
If Pi-hole is not installed, the script will install it.

### Prerequisites

Don't forget to make the script executable.
```
chmod +x lazy_secure
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
 -x  --debug		debug (dev-debug.log )
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
