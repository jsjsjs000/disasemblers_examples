SHELL := /bin/bash
rootfs = /home/jarsulk/phyLinux/build/tmp/work/phyboard_pollux_imx8mp_3-phytec-linux/pco-ml-image/1.0-r0/rootfs/

all:
	# @source env.sh
	@mkdir -p build/

	@cp $(rootfs)/lib/libc.so.6 build/

	source env.sh
	echo $$ENV{CC} hello_world.c -o build/hello_world

clean:
	rm -f build/*
