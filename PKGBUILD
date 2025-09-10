# Maintainer: Ambroise Hervillard (cashlloc) <ahervillard@pm.me>

pkgname="network-usemein"
pkgver=0
pkgrel=3
pkgdesc="Network utilities for Usemein"
url="https://cashlloc.github.io"
arch=('any')
license=('MIT')

depends=(
  'net-tools' 'networkmanager'
  'wireguard-tools'
)

package(){
  install -Dm644 "$srcdir/80-network-usemein.preset" "$pkgdir/usr/lib/systemd/system-preset/80-network-usemein.preset"
}
