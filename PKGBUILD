pkgname=ekatra-fonts
pkgdesc="Free high quality Gujarati TrueType fonts provided by Ekatra Foundation"
pkgver=240114
pkgrel=1
license=('Custom:Ekatra')
arch=('x86_64')
depends=('fontconfig')
url="http://www.ekatrafoundation.org/%E0%AA%8F%E0%AA%95%E0%AA%A4%E0%AB%8D%E0%AA%B0-%E0%AA%AB%E0%AB%8B%E0%AA%A8%E0%AB%8D%E0%AA%9F/"
source=(http://www.ekatrafoundation.org/wp-content/uploads/fonts/Ekatrafonts.zip)
sha512sums=('0d0a13d28ad883d5d307258a5a743df5b63f78b1cce43161101b403f052091ff1d252eab9490887972ce053fb9611898526cff9bbaee877ce1e78701b1831d56')
install=ekatra-fonts.install

package() {
	install -d $pkgdir/usr/share/fonts/ekatra
	install -m0644 Ekatrafonts/*.ttf ${pkgdir}/usr/share/fonts/ekatra
}
