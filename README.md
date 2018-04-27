IBus-Unikey IME
===============

ibus-unikey is an [IBus](https://github.com/ibus/ibus) IME.
It use Unikey-engine for progress key event.
(a modified version of it)

### [Cần người tiếp tục phát triển & bảo trì dự án](https://github.com/vn-input/ibus-unikey/issues/14)

Please read [INSTALL](./INSTALL) for how to install


## Install from source
```sh
sudo apt install autopoint intltool libtool pkg-config libibus-1.0-dev libx11-dev libgtk2.0-dev
ln -s README.md README
./autogen.sh
make
sudo make install
```
