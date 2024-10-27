# screen share not working
1. #### check 
````1.```` setting > ````2.```` System > ````3.```` about > ````4.```` system > ````5.```` detalis

#### if your windowing system is  Wayland follow next step

2. ### open terminal
```sh
sudo nano /etc/gdm3/custom.conf
```
3. ### change 
 ``
 #WaylandEnable=false to WaylandEnable=false
 ``
```sh
sudo reboot
```
