# Maintainer: Loren Copeland < thisisquitealongname at gm--l dot com >

pkgname=vst-ccernaudio-plugins
pkgver=20100617
pkgrel=1
pkgdesc="Set of vst plugins by ccern.audio"
arch=("i686")
url="http://sites.google.com/site/ccernaudio/vst-plugins"
license="unknown"
source="https://sites.google.com/site/ccernnaudio/files/backup-vst-linux.zip"

build () {
cd "${srcdir}"
mkdir -p "${pkgdir}/usr/lib/vst"
cp *.so "${pkgdir}/usr/lib/vst"
chmod 755 "${pkgdir}/usr/lib/vst/"*.so
}

# vim:set ts=2 sw=2 et:
md5sums=('72a6ef3db124ac34fc8ab3823e001815')
