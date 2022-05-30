pkgname=holoiso-updateclient
pkgver="rel.$(date +%Y%m%d.%H%M)"
pkgdesc="HoloISO Update Client"
pkgrel="1"
arch=("x86_64")

package() {
    mkdir -p "${pkgdir}/usr/bin"
    cp "${srcdir}/steamos-update" "${pkgdir}/usr/bin/steamos-update"
    chmod +x "${pkgdir}/usr/bin/steamos-update"
}

