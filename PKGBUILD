# Maintainer: minhmc2077 (quangminh21072010@gmail.com)
pkgname=fastmirror
pkgver=1.0
pkgrel=1
pkgdesc="A simple tool to calculate and apply the fastest Arch Linux mirrors"
arch=('any')
url="https://github.com/minhmc2007/fastmirror" 
license=('MIT')
depends=('python' 'python-requests')
source=("fastmirror.py")
sha256sums=('SKIP') 

package() {
    # Install the script to /usr/bin/ and make it executable
    install -Dm755 "${srcdir}/fastmirror.py" "${pkgdir}/usr/bin/fastmirror"
}
