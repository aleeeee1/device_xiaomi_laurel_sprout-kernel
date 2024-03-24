# How to generate kernel-headers

In kernel dir
```
make ARCH=arm64 INSTALL_HDR_PATH="./kernel-headers/" headers_install
```

Then move kernel-headers here.
