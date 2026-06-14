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
source=(
    "jupyter_mimetypes-$pkgver.tar.gz::https://files.pythonhosted.org/packages/source/g/jupyter-mimetypes/jupyter_mimetypes-$pkgver.tar.gz"
)
sha256sums=('SKIP')

build() {
    cd "jupyter_mimetypes-$pkgver"
    python -m build --wheel --no-isolation
}

package() {
    cd "jupyter_mimetypes-$pkgver"
    python -m installer --destdir="$pkgdir" dist/*.whl
}
