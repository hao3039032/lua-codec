all:
	gcc -Wall -O2 -shared -o ../test/codec.so codec.c aes.c pkcs7_padding.c -I /usr/local/Cellar/lua/5.4.3/include/lua5.4 -L /usr/local/Cellar/lua/5.4.3/lib -lcrypto -lssl -llua

clean:
	rm -f codec.so
