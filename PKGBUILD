# Maintainer: MatuusModder
pkgname=(matuusos-sddm-config)
pkgrel='1'
pkgver=1
pkgdesc="Default SDDM theme for MatuusOS"
arch=('any')
license=('GPL3')
depends=('sddm>=0.18')
makedepends=('git')
provides=("matuusos-sddm-config")
conflicts=("matuusos-sddm-config")
source=('sugar-candy::git+https://github.com/MatusModder/sddm-config-matuusos.git')
sha256sums=('SKIP')

prepare() {
git clone https://github.com/MatusModder/sddm-config-matuusos.git
cd sddm-config-matuusos
}

install() {
    install -Dm644 sddm.conf /etc
}