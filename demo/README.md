0.用sdkmanager安装35.6版本的系统

Install Jetson Linux 35.6.0 with sdkmanager.

1.在/boot目录下建立一个新的文件夹xen1

cd /boot

sudo mkdir xen1

2.将所有文件拷贝到xen1中

sudo cp * /boot/xen1

3.将extlinux.conf拷贝到/boot/extlinux中

sudo cp extlinux.conf /boot/extlinux

4.重启，选择系统是按1进入xen

Reset, press 1 in system choose window
