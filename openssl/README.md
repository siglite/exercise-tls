# OpenSSL 1.1.0

## Download and Install

```
$ mkdir -p $HOME/local/build && cd $HOME/local/build
$ curl -O https://www.openssl.org/source/openssl-1.1.0i.tar.gz
$ tar xvf openssl-1.1.0i.tar.gz
$ mkdir build-openssl && cd build-openssl
$ export PKGROOT=$HOME/local/stow/openssl-1.1.0i
$ ../openssl-1.1.0i/config --prefix=$PKGROOT --openssldir=$PKGROOT/etc/ssl
$ make && make test && make install
```

## References

* [INSTALL](https://github.com/openssl/openssl/blob/master/INSTALL)
