# Generated by debtap
# Maintainer: FengYu<abcfy2@163.com>
pkgname=ukylin-wine
pkgver=70.6.3.25
pkgrel=1
pkgdesc="Base ukylin-wine package. Full description can be found here: https://www.ubuntukylin.com/news/1682-cn.html . Issues and pull request please send to github: https://github.com/abcfy2/ukylin-wine-aur/"
provides=('ukylin-wine')
arch=('i686' 'x86_64')
url="https://www.kylinos.cn"
license=('proprietary')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source=("http://archive.ubuntukylin.com/software/pool/partner/ukylin-wine_${pkgver}_amd64.deb")
md5sums=('6edd8e055ea733a3f903150fdf0c19c7')
depends=('polkit')
makedepends=('tar')

package() {
  # Extract package data
  tar xf data.tar.xz -C "${pkgdir}"
}
