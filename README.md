TWRP FOR EVERCOSS A66A MT6582 Soc.

## Required ##
---------------
	KERNEL : PREBUILT KERNEL 3.4.67

## Manifest ##
---------------
	https://github.com/dheaapriandi/twrp_manifest

## How to build ##
---------------

	$ cd (TWRP REPO)

	$ source build/envsetup.sh 

	$ lunch omni_a66a-eng 

	$ make clean && make -j2 recoveryimage