# Maintainer: Ezilei Correia <ezilei@yahoo.com.br>


pkgname=archmaker
pkgver=$(date +%y.%m.%d)
pkgrel=1
pkgdesc="Quickly and easily create your own arch-based GNU/Linux-distribution"
arch=('any')
license=('GPL')
url="https://github.com/guidedlinux/archmaker"
depends=('git' 'QT5' 'archiso' 'xterm')
source=("git+https://github.com/guidedlinux/archmaker.git")
md5sums=(SKIP)


package() {
    
    cd archmaker
    mkdir build && cd build
    qmake ..
    make
    sudo make install

}
