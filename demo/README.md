1.在/boot目录下建立一个新的文件夹xen1
cd /boot
sudo mkdir xen1
2.将所有文件拷贝到xen1中
sudo cp * /boot/xen1
3.将extlinux.conf拷贝到/boot/extlinux中
sudo cp extlinux.conf /boot/extlinux