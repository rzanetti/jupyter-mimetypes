#!/usr/bin/env bash
# -*- mode: sh; mode: sh-bash -*-
# shellcheck disable=SC2034,SC2154,SC2164

pkgname=python-jupyter-mimetypes
pkgver=0.2.0
pkgrel=1
pkgdesc="Enhanced Jupyter representation capabilities through proxy objects"
arch=('x86_64')
url="https://github.com/datalayer/jupyter-mimetypes"
license=('BSD-3-Clause')
depends=(
    'python'
    'python-pyarrow'
    'python-typing_extensions'
)
makedepends=(
    'python-installer'
)
source=(
    "jupyter_mimetypes-$pkgver-py3-none-any.whl::https://files.pythonhosted.org/packages/72/45/cb4671e13fed39f721066ad1a00714d4b607982b8d3e97a25f836198d1df/jupyter_mimetypes-$pkgver-py3-none-any.whl"
)
sha256sums=(
    'e6dcd989258e3fc944365b656d9173191517e0e393bd878e97ce500e5b388527'
)
package() {
    python -m installer \
        --destdir="$pkgdir" \
        "jupyter_mimetypes-$pkgver-py3-none-any.whl"
}
