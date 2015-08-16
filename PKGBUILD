# Daniel Kirchner <daniel at ekpyron dot org>
pkgname=mingw32-opencl-headers
pkgver=1.1.20110526
pkgrel=2
pkgdesc="OpenCL (Open Computing Language) header files (mingw32 symlinks)"
arch=('any')
license=('custom')
url='http://www.khronos.org/registry/cl/'
depends=('opencl-headers')

_targetarch=i486-mingw32

package() {
	mkdir -p $pkgdir/usr/$_targetarch/include
	ln -s ../../../usr/include/CL $pkgdir/usr/$_targetarch/include
}
