# Contributor: onexused <aursignup dot kyoo at xoxy dot net>
pkgname=python-distribute-extra
pkgver=2.37
pkgrel=1
pkgdesc="Easily integrate gettext support, themed icons and scrollkeeper based documentation into Python's distutils."
arch=('any')
url="https://launchpad.net/python-distutils-extra"
license=('GPL')
groups=()
makedepends=('intltool' 'pygobject' 'python-httplib2')
depends=('python-distribute')
options=('!emptydirs')
source=("https://launchpad.net/python-distutils-extra/trunk/${pkgver}/+download/python-distutils-extra-${pkgver}.tar.gz")
md5sums=('52cffcd6e8e17ed5aa2f9303683333ef')

package() {
	cd "${srcdir}/python-distutils-extra-${pkgver}"
	python setup.py install --root="$pkgdir/" --optimize=1
}

