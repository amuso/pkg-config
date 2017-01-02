# pkg-config for Mac OS X
## Version 0.29.1

Read more at https://www.freedesktop.org/wiki/Software/pkg-config/
For building rtl-sdr (and other software packages)

## Requirements

- Xcode command line tools

## Building

```
xcode-select --install
```

```
wget https://pkg-config.freedesktop.org/releases/pkg-config-0.29.1.tar.gz
tar -zxvpf pkg-config-0.29.1.tar.gz
cd pkg-config-0.29.1
./configure --with-internal-glib
make
sudo make install
```

