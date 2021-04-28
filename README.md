This repository contains the configuration file for the [Surge](https://nssurge.com) app to block domains from the Steven Black’s unified [hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts).

There are three ways to use this domain set:

- Download `hosts.txt` to the Surge configuration directory and add the following line

    ```
    DOMAIN-SET,hosts.txt,REJECT
    ```
    in the `[Rule]` section before the `FINAL` line of your own configuration file. There's no automatic update using this method.
    
- Download the `Firewall.conf` file and import it into Surge. The domain set is automatically updated from this repository.

- You can also add the following line 

    ```
    DOMAIN-SET,https://raw.githubusercontent.com/Taxyovio/Surge-Firewall/main/hosts.txt,REJECT
    ```
    in the `[Rule]` section before the `FINAL` line of your own configuration file. The domain set is automatically updated from this repository.