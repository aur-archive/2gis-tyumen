pkgname=2gis-tyumen
pkgver=91
pkgrel=1
pkgdesc="Map of Tyumen for 2GIS, June 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/tyumen/products/download#linux"
license=('custom')
depends=('2gis>=3.14.6.0')
source=("http://download.2gis.com/arhives/2GISData_Tyumen-91.orig.zip")
md5sums=('db8a8bc19476927d560e3b79998c96d4')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Tyumen.dgdat" "${pkgdir}/opt/2gis/2gis-tyumen.dgdat" || return 1
  
}
