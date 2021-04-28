This repository contains the configuration file for the [Surge](https://nssurge.com) app to block domains from the Steven Black’s unified [hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts).

To use the configuration file directly, download the `Firewall.conf` file and import it into Surge.

You can also add the following line 

```
DOMAIN-SET,https://raw.githubusercontent.com/Taxyovio/Surge-Firewall/main/hosts.txt,REJECT
```

in the `[Rule]` section before the `FINAL` line of your own configuration file.