# linux_OS_docker
Folder "popular_linux_os" save popular linux os dockerfile.

In order to execute binary files of different kernels, ubuntu_x64_qemu installs qemu-user-static and binfmt_misc.


# reference
Build image of arm architecture on x86 machine
  https://zhuanlan.zhihu.com/p/106054643
  
# note
tshark need add arg when docker run
'''
 docker run -it --cap-add=NET_RAW --cap-add=NET_ADMIN image_name
'''