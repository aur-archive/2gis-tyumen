# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-tyumen
pkgver=67
pkgrel=1
pkgdesc="Map of Tyumen for 2GIS, June 2012"
arch=('i686' 'x86_64')
url="http://tyumen.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.6.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Tyumen-67.orig.zip")
md5sums=('b2db74d2435f9959a0146306b868e22b')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tyumen.dgdat "${startdir}/pkg/opt/2gis/tyumen.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tyumen.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tyumen.dglf" || return 1
     
}

