# screen share not working
1. #### check 
````.```` setting -> ````.```` System -> ````.```` about -> ````.```` system -> ````.```` detalis

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
