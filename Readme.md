# Compilation
## Obtain the dependent source code
``` git submodule init ```: register submodule 
``` git submodule update ```: pull the libevent module

## Compile the libevent
``` bash
$ cd deps/libevent-2.1
$ ./autogent.sh
$ ./configure --disable-openssl
$ make
```

## Compile the websocket

``` bash
make
```