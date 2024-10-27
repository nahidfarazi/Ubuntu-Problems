# Unable-disk-access

1. ### check your disk
 ```sh 1
 sudo fdisk -l
 ```
2. ### insall package
 ```sh 2
sudo apt install nfs-common && sudo apt install cifs-utils
```
3. ### fix your disk 
```sh 4
sudo ntfsfix -d /dev/<your disk name>
```
### example
``sh
sudo ntfsfix -d /dev/sda10
``
