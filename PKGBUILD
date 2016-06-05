# Maintainer: Julian Brost <julian@0x4a42.net>
pkgname=grub-theme-dieses-system-ist-sicher
pkgver=1
pkgrel=1
epoch=
pkgdesc=""
arch=("any")
url=""
license=()
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("theme.txt"
        "sicher.png")
noextract=()
sha256sums=('SKIP'
            'SKIP')
validpgpkeys=()

#prepare() {
#	cd "$pkgname-$pkgver"
#	patch -p1 -i "$srcdir/$pkgname-$pkgver.patch"
#}
#
#build() {
#	cd "$pkgname-$pkgver"
#	./configure --prefix=/usr
#	make
#}
#
#check() {
#	cd "$pkgname-$pkgver"
#	make -k check
#}

package() {
	local dest="$pkgdir/usr/share/grub/themes/dieses-system-ist-sicher"
	install -d "$dest"
	for file in "${source[@]}"; do
		install -m644 "$file" "$dest/$file"
	done
}
