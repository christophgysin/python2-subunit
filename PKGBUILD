# Contributor: Christoph Gysin <christoph.gysin@gmail.com>
pkgname=python2-subunit
_pkgname=python-subunit
pkgver=0.0.18
pkgrel=1
pkgdesc="Subunit is a streaming protocol for test results."
arch=('any')
makedepends=('setuptools')
depends=()
url="https://launchpad.net/subunit"
license=('Apache License')
source=(http://launchpad.net/subunit/trunk/${pkgver}/+download/${_pkgname}-${pkgver}.tar.gz)
md5sums=('c3f99c1fbc3e93f064d1e16fa78f70cd')

package() {
    cd ${srcdir}/${_pkgname}-${pkgver}
    python2 setup.py install --prefix=/usr --root=${pkgdir}
}
