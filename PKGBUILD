# Maintainer: Jeremy Baxter <jtbx@disroot.org>

pkgname=virbos-livescripts
pkgver=0.1.0
pkgrel=1
pkgdesc="Scripts used in the Virbos ISO"
arch=("any")
url="https://github.com/Virbos/virbos-livescripts"
license=("GPL")
depends=("bash")
source=("https://raw.githubusercontent.com/Virbos/virbos-livescripts/master/virbos-setup")
sha256sums=("SKIP")

package() {
	mkdir -p "${pkgdir}"/usr/bin
	install -m755 "${srcdir}"/virbos-setup "${pkgdir}"/usr/bin
}
