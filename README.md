prereq:
	linaro arm-gcc 4.6 or 4.7
	(easier way is ubuntu >=12 with apt-get install build-essential gcc-arm-linux-gnueabi libncurses5-dev)

Build command:

kernel
======
	cd <kernel path>
	../abuild.sh clean
	../abuild.sh release

general notes:
==============
 most tweaks taken from excellent works from: https://github.com/varunchitre15/thunderzap_canvas_2/
 kernel source from wikogeek 4.0.4 for wiko cink peax

v0.1:
=====
 - CPU overclock O/C 1.2Ghz
 - performance: Turn CPUs online while active
 - VFP compil with neon
