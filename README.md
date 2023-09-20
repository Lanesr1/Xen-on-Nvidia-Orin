# Xen-on-Nvidia-Orin
 Run Xen hypervisor on Nvidia chips

 目标：同时在AGX Orin上运行Xen和FreeRTOS
 Target: Run both Xen and FreeRTOS on AGX Orin

 硬件平台：Nvidia AGX Orin 32GB
 Hardware platform: Nvidia AGX Orin 32GB

 进度：20%
 Progress: 20%

第一步：未知位置反复重启。
First step: Board resets in unknown position repeatly. 
 ![本地路径](./pic/1.JPG) 

第二步：Xen正常启动，dom0已加载，内核未启动。
Second step: Xen boots normally, dom0 has been loaded, but kernel didn't startup. 
 ![本地路径](./pic/2.JPG) 

第三步：内核已启动，途中报错，开始慢慢排错。
Third Step: Kernel has started and some errors showup. Dealing with that slowly.
 ![本地路径](./pic/3.JPG) 
