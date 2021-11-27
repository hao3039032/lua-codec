all:
	gcc -Wall -O2 -shared -o codec.so codec.c -I /usr/local/Cellar/lua/5.4.3/include/lua5.4 -lcrypto -lssl

clean:
	rm -f codec.so
