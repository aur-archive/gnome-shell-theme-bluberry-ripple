### Author: ~theRealPadster <http://therealpadster.deviantart.com/>
# Maintainer: Charles Briere <charlesbriere dot flatzo at gmail dot com>

pkgname=gnome-shell-theme-bluberry-ripple
pkgver=1.11
pkgrel=1
pkgdesc="Blueberry Ripple GNOME Shell Theme"
url="http://therealpadster.deviantart.com/art/Contrail-313169671?q=gallery%3Atherealpadster%2F26241833&qo=7"
license=('cc-by-nc-sa-3.0')
arch=('any')
depends=('gnome-shell')
makedepends=('unzip')
optdepends=('gnome-shell-extension-user-theme: User Theme extension for GNOME Shell'
            'gnome-tweak-tool: A tool to customize advanced GNOME 3 options.')
source=(http://orig02.deviantart.net/3520/f/2012/140/e/7/blueberry_ripple_by_therealpadster-d4phk77.zip)
DLAGENTS=('http::/usr/bin/wget -c -t 3 --waitretry=3 -H -U Mozilla -O %o %u')
md5sums=('2c11c29531673fb838c85aff49763ec4')



package() {
  mkdir -p ${pkgdir}/usr/share/themes/Blueberry_Ripple

  unzip -o blueberry_ripple_by_therealpadster-d4phk77.zip
  ls -lrta $srcdir
  cp -R $srcdir/Blueberry\ Ripple/gnome-shell $pkgdir/usr/share/themes/Blueberry_Ripple/

  chmod -R 755 ${pkgdir}/usr/share/themes/Blueberry_Ripple
}



