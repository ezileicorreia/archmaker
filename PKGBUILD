# Maintainer: Ezilei Correia <ezilei@yahoo.com.br>


pkgname=archmaker
pkgver=$(date +%y.%m.%d)
pkgrel=1
pkgdesc="Quickly and easily create your own arch-based GNU/Linux-distribution"
arch=('any')
license=('GPL')
url="https://github.com/ezileicorreia/archmaker"
depends=('git' 'qt5-base' 'archiso' 'xterm')
source=("git+https://github.com/ezileicorreia/archmaker.git")
md5sums=(SKIP)


package() {
    
    cd archmaker
    mkdir build && cd build
    qmake ..
    make
    sudo make install

}
