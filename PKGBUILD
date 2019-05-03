pkgname=pyright
pkgver=1.0.22
pkgrel=1
epoch=
pkgdesc="Static type checker for Python "
arch=('any')
url="https://github.com/Microsoft/pyright/"
license=('MIT')
depends=()
makedepends=('npm')
source=("https://registry.npmjs.org/$pkgname/-/$pkgname-$pkgver.tgz")
noextract=($pkgname-$pkgver.tgz)
md5sums=('bbf7c481c1fdc2d9748a2f705f699b87')

package() {
    npm install -g --user root --prefix "$pkgdir"/usr "$srcdir"/$pkgname-$pkgver.tgz
}
