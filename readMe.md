I would like to use this repo to save some of the things that I've used to setup other raspberry pis
 

This needs to be flushed out, but I needed a place to save and remember these things


Add disable-wlan-if-eth to /etc/init.d/
sudo chmod 755 /etc/init.d/disable-wlan-if-eth
sudo vim /etc/rc.local and add `sudo /etc/init.d/disable-wlan-if-eth` before exit 0 maybe don't need sudo
