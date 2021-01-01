# Maintainer: Caspar Friedrich <c.s.w.friedrich@gmail.com>

pkgname=ti-pru-cgt
pkgver=2.3.3
pkgrel=1
pkgdesc="TI PRU code generation tools"
arch=("armv7h")
url="https://www.ti.com/tool/PRU-CGT"
license=('GPL')
groups=()
depends=()
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=(http://software-dl.ti.com/codegen/esd/cgt_public_sw/PRU/${pkgver}/ti_cgt_pru_${pkgver}_armlinuxa8hf_busybox_installer.sh)
noextract=()
sha256sums=(8390cb77b46b728ce2940595b81406f76d86dfed58c21258e3206a7c1232ccf2)

build() {
	cd ${srcdir}
	chmod +x ti_cgt_pru_${pkgver}_armlinuxa8hf_busybox_installer.sh

}

package() {
	cd ${srcdir}
	./ti_cgt_pru_${pkgver}_armlinuxa8hf_busybox_installer.sh --prefix ${pkgdir}
}
