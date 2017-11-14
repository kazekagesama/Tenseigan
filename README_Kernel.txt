HOW TO BUILD KERNEL FOR SM-A500H_SWA_MM_DD

1. How to Build
	- get Toolchain
		From android git server , codesourcery and etc ..
		 -  arm-eabi-4.8-
	$ build_kernel.sh

2. Output filesS
	- Kernel : output/arch/arm/boot/zImage
	- module : output/drivers/*/*.ko

3. How to Clean	
		$ cd output
		$ make clean
			
4. How to make .tar binary for downloading into target.
	- change current directory to Kernel/arch/arm/boot
	- type following command
	$ tar cvf SM-A500H_SWA_MM_DD.tar zImage
		
		
		