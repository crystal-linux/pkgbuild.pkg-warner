# Crystal Maintainer: echo -n 'bWF0dEBnZXRjcnlzdC5hbA==' | base64 --decode
pkgname=pkg_warner
pkgver=1.0
pkgrel=1
pkgdesc="A helpful script if you use the wrong package manager"
arch=('any')
url="https://github.com/crystal-linux/pkg-warner"
license=('GPL')
provides=($pkgname)
conflicts=($pkgname)
depends=('bash')
source=('warner')
install="warner.install"
md5sums=('02ce7e9e8c29c3d110ca2280ac1cdfcf')

package() {
  chmod +x warner
  mkdir -p ${pkgdir}/usr/bin
  cp warner ${pkgdir}/usr/bin/pkg-warner
}
