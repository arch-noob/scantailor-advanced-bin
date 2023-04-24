# Maintainer: Roman Vasilev <2rvasilev at live dot ru>

pkgname=scantailor-advanced-bin
pkgver=v1.0.18
pkgrel=3
pkgdesc="Interactive post-processing tool for scanned pages that merges the features of the ScanTailor Featured and ScanTailor Enhanced versions, brings new ones and fixes. "
arch=("x86_64")
# url="https://github.com/4lex4/scantailor-advanced"
url="https://github.com/ScanTailor-Advanced/scantailor-advanced"
license=("GPL3")
depends=(
    "boost-libs"
    "libjpeg"
    "libpng"
    "libtiff"
    "qt5-base"
    "zlib"
    )
makedepends=()
provides=("scantailor")
conflicts=("scantailor-advanced-git")
# source=("$pkgname-$pkgver.tar.xz::https://f002.backblazeb2.com/file/AUR-Store/$pkgname/scantailor-advanced-git-$pkgver.$arch.tar.xz")
source=("$pkgname-$pkgver.tar.gz::https://github.com/arch-noob/scantailor-advanced-bin/releases/download/$pkgver/scantailor-advanced-$pkgver.tar.gz")
sha256sums=('9b39cfeac128ad5cfeff8a7026007c3f570f9f75cce0b25bf04e2ef9e5583a38')

package() {
  cd $srcdir
  cp -dpr --no-preserve=ownership usr/ "$pkgdir/usr/"
}
