[![Build Status](https://travis-ci.org/bitprim/bitprim-client.svg?branch=master)](https://travis-ci.org/bitprim/bitprim-client)

# Bitprim Client

*Bitcoin Client Query Library*

Make sure you have installed [bitprim-core](https://github.com/bitprim/bitprim-core) and [bitprim-protocol](https://github.com/bitprim/bitprim-protocol) beforehand according to its build instructions.

```
$ git clone https://github.com/bitprim/bitprim-client.git
$ cd bitprim-client
$ mkdir build
$ cd build
$ cmake .. -DWITH_TESTS=OFF -DWITH_EXAMPLES=OFF -DCMAKE_BUILD_TYPE=Release -DCMAKE_CXX_FLAGS="-std=c++11" 
$ make -j2 
$ sudo make install
```

bitprim-client is now installed in `/usr/local/`.
