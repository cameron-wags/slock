pkgname=slock
pkgver=1.4_p1.0
pkgrel=1
epoch=
pkgdesc="Simple screen locker"
arch=("any")
url="https://github.com/cameron-wags/slock"
license=("MIT")
depends=()
source=("$pkgname-$pkgver.tar.gz::$url/archive/refs/tags/$pkgver.tar.gz")
md5sums=("SKIP")

build() {
    cd "$pkgname-$pkgver"
    make $pkgname
}

package() {
    make DESTDIR="$pkgdir" install
}
