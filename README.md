# RdkPkg
This repository holds reference implementation of UEFI based RDK secure boot loader and DRI for Hikey platform.

for hikey platform
 usage:
 
	./build rootfs   - yocto Hikey build for kernel , initramfs and rootfs 
	
	./build edk2     - UEFI Hikey firmware , RDK bootlaoder and DRI
	
	./build image    - signing the images , creating  key pair and system image
	
	./build flash    - flsah the images on Hikey 


for more information refer UEFI_RDK.doc
