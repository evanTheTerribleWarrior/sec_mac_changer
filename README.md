# Mac_changer
> This is just a simple alternative to the standard Kali Linux macchanger

## Usage example

The module uses "ip" instead of ifconfig but you can extend it

```sh
Options:
-i: The network interface e.g. eth0, wlan0...
-r: To generate a random MAC
-m: To specify your own MAC

[sudo] mac_changer -i wlan0 -r
[sudo] mac_changer -i wlan0 -m aa:bb:cc:dd:ee:ff
```
