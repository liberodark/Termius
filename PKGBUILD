# Maintainer: liberodark

pkgname=termius
pkgver=7.0.1
pkgrel=1
pkgdesc="An elegant GUI for Git."
arch=('x86_64')
url="https://termius.com/"
license=('Custom')
depends=('xdg-utils')
source_x86_64=("https://deb.termius.com/pool/main/t/termius-app/termius-app_${pkgver}_amd64.deb")
sha512sums_x86_64=('0ef72e672da6c5e300355aba891869eba264ff7e248821edd8acdd7a94172636f32ec96ca4c85a5af14e0437f679f6aa235fd08fcece58e0df51ff1ea2cc24e7')
        
package() {
  cd $srcdir
  tar xvf data.tar.xz
  cp -r usr $pkgdir
  cp -r opt $pkgdir
}

