# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-tyumen
pkgver=56
pkgrel=1
pkgdesc="Map of Tyumen for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Tyumen-${pkgver}.orig.zip")
md5sums=('4129a4134c23d62f5ff33efd9be1b8e9')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tyumen.dgdat "${startdir}/pkg/opt/2gis/tyumen.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tyumen.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tyumen.dglf" || return 1
     
}

