# macOS

```sh
$ tar -zxvf HTK-3.4.1.tar.gz
$ export CPPFLAGS=-UPHNALG
$ ./configure --without-x --disable-hslab
$ make all
$ sudo make install
```

```sh
$ unzip HTK-3.4.1.zip
$ export CPPFLAGS=-UPHNALG
$ ./configure --without-x --disable-hslab
$ make all
$ make install # may need chmod 744
```