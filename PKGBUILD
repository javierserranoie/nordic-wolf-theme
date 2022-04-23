# Maintainer: Javier Serrano <javiserranoie@gmail.com>
pkgname=nordic-wolf-theme
pkgver=0.0.1
pkgrel=1
pkgdesc="Nordic theme + Papirus icons + Wolf background"
arch=(x86_64)
url=""
license=('MIT')
groups=()
depends=()
checkdepends=()
optdepends=()
backup=()
options=(!lto)
install=
changelog=
source=("$pkgname-$pkgver.tar.gz")
noextract=()
md5sums=()
validpgpkeys=()

package() {
	cd "$srcdir/$pkgname-$pkgver"
	#install -Dm644 wolf.png "$pkgdir/usr/share/backgrounds/wolf.png"
	make VERSION=$pkgver DESTDIR="$pkgdir" PREFIX="/usr/share" setup install
}
sha256sums=('811cc07b1e40a69db8159c3116e2011e06583434cac0a231f2adaa90300f8d95')
