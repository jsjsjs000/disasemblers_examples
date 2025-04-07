SHELL := /bin/bash
rootfs = /home/p2119/phyLinux/build/tmp/work/phyboard_pollux_imx8mp_3-phytec-linux/pco-ml-image/1.0-r0/rootfs

all:
	@mkdir -p build/

	@cp $(rootfs)/lib/libc.so.6 build/

		@# required in one line for variables
	source env.sh; \
	$${CC} hello_world.c -o build/hello_world

clean:
	rm -f build/*
