# Maintainer: tenshi (pwoertnehsi@gmail.com)
pkgname=droidvalds-git
pkgver=1.0
pkgrel=1
install=droidvalds.install
pkgdesc="SystemD Linus Droidvalds GCC Virus"
arch=('any')
depends=('mpv' 'xorg-xrandr' 'bash')
license=('GPL')

source=()

package() {
    install -Dm755 "${srcdir}/usr/bin/droidvalds" "${pkgdir}/usr/bin/droidvalds"
    
    install -d "${pkgdir}/usr/share/droidvalds"
    cp "${srcdir}/usr/share/droidvalds/"*.mp4 "${pkgdir}/usr/share/droidvalds/"
    
    install -Dm644 "${srcdir}/usr/lib/systemd/user/droidvalds.service" \
                   "${pkgdir}/usr/lib/systemd/user/droidvalds.service"
}
