# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-dunst-config
pkgver=1
pkgrel=1
pkgdesc="Dunst config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('dunst')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/dunst/"
    install -Dm 644 "dunstrc" "${pkgdir}/etc/skel/.config/dunst/dunst.conf"
}
