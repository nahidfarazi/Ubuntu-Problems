# Unable-disk-access
1. ### check your disk
 ```sh 1
 sudo fdisk -l
 ```
2. ### insall package
 ```sh 2
sudo apt install nfs-common
```
 ```sh 3
 sudo apt install cifs-utils
 ```
3. ### fix your disk 
```sh 4
sudo ntfsfix -d /dev/<your disk name>
```
