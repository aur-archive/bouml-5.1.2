# Maintainer: cros_145  <joner14@hotmail.com>
# Contributor: cros_145<joner14@hotmail.com>


pkgname=bouml-5.1.2
pkgver=5.1.2
pkgrel=1
pkgdesc='A free UML 2 modeler with C++, Idl, Java, PHP and Python code generation'
arch=('i686')
options=('!strip')
url='http://bouml.fr/'
license=('GPL')
depends=('qt3')
makedepends=('rpmextract')
source=("http://bouml.free.fr/files/bouml-5.1.2-CentOS6.i686.rpm")
md5sums=('74e4ce46e518233141b1c9625028b960')

build() {
         cd $startdir/pkg
	rpmextract.sh $startdir/src/bouml-5.1.2-CentOS6.i686.rpm
}
