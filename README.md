# RdkPkg
This repository holds reference implementation of UEFI based RDK secure boot loader and DRI for Hikey platform.

for hikey platform
 usage:
	./build rootfs   - yocto build for kernel , initramfs and rootfs
	
	./build edk2     - UEFI firmware and RDK bootlaoder and DRI
	
	./build image    - signing the images and create key pair
	
	./build flash    - flsah the images on Hikey 
