# DP-LKernel Beta   
**Data Protection Linux Kernel Beta**   


## Summary   
This project is a Linux Kernel for high-speed nonvolatile memory.   
I have improved for high-speed nonvolatile memory based on Linux-3.12.66 source code.   


## How to
Build and Boot DP-LKernel   
```
# ./do.sh   
# reboot   
```

Boot DP-LKernel   
```
# ./set_grub.sh nvm   
# reboot   
```

Boot Default Linux Kernel   
```
# ./set_grub.sh default   
# reboot   
```


## File System   
- [pramfs](http://pramfs.sourceforge.net)  (Original File System)   
- [improved-pramfs](https://github.com/kohga/improved-pramfs)  (Improved File System)   


## Support
- Debian
- Ubuntu
- CentOS
- Fedora
- Red Hat Enterprise Linux


## Official Version
[dp-lkernel](https://github.com/kohga/dp-lkernel)   


## Reference   
PRAMFSにおける誤書き込みからのデータ保護機能, 電子情報通信学会総合大会講演論文集 2016年_情報システム(1), 55,   
2016-03-01, 一般社団法人電子情報通信学会   
>- <http://www.gakkai-web.net/gakkai/ieice/G_2016/Settings/ab/d_06_001.html>   
>- <http://ci.nii.ac.jp/naid/110010036689>   

