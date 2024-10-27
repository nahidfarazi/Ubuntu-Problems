# Unable-disk-access
1.#### check your disk
 ```sh 1
 sudo fdisk -l
 ```
 ```sh 2
sudo apt install nfs-common
```
 ```sh 3
 sudo apt install cifs-utils
 ```
```sh 4
sudo ntfsfix -d /dev/<your disk name>
```
