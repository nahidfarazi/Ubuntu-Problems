# ssh Permission denied

1. ### open sshd config
```sh
sudo nano /etc/ssh/sshd_config
```
## uncomment port and PasswordAuthentication
2. ### change like
```
#port 22 to port 22
#PasswordAuthentication yes  to PasswordAuthentication yes
```
3. ### Reboot your System
```sh
sudo reboot
```
