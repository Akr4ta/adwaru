# Maintainer: Akrata
pkgname=adwaru
pkgver=1.0.0
pkgrel=1
pkgdesc="XXXX"
arch=("any")
url="https://github.com/Akr4ta/adwaru"
license=("GPL3")
depends=(adwaita-icon-theme)
makedepends=(git)
source=("git+${url}.git")
#source=("${pkgname}-${pkgver}.tar.gz::https://github.com/Akr4ta/${pkgname}/archive/v${pkgver}.tar.gz")
sha256sums=('SKIP')

package() {
  cd "${pkgname}"

  install -dm755 "${pkgdir}/usr/share/icons/"
  cp -r adwaru-cursor "${pkgdir}/usr/share/icons/"
  cp -r adwaru-purple "${pkgdir}/usr/share/icons/"
}
