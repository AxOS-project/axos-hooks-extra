# Maintainer: Aditya Shakya <adi1090x@gmail.com>

pkgname="axos-hooks-extra"
pkgver=3.3
pkgrel=1
pkgdesc='Extra pacman hooks for AxOS'
arch=('x86_64')
license=('GPL3')
source=(
		'axos-hook-grub.hook'
		'axos-hooks-extra'
)

package() {
  local hooks="$pkgdir"/usr/share/libalpm/hooks
  local bin="$pkgdir"/usr/bin

  install -Dm 644 axos-hook-grub.hook  		"$hooks"/axos-hook-grub.hook
  install -Dm 755 axos-hooks-extra       		"$bin"/axos-hooks-extra
}
sha256sums=('9802a4f6235f378df078a55cc73bb06a6ccae113928dcd39de3dbe5ad1ad42fb'
            'e5e582946e79d092e19fa703edbf6ea7e2849f7e815e62d80dd3696a1821502e')
