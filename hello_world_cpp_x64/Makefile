all:
	mkdir -p build/

	cp /lib/x86_64-linux-gnu/libc.so.6 build/
	cp /lib/x86_64-linux-gnu/libstdc++.so.6 build/

	gcc hello_world.cpp -o build/hello_world -lstdc++

clean:
	rm -rf build/*
