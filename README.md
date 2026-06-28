# Jupyter MIME Types PKGBUILD

A [Python](https://www.python.org) package that provides enhanced [Jupyter](https://jupyter.org) representation capabilities through proxy objects, enabling efficient [Apache Arrow-based](https://arrow.apache.org) serialization for [pandas](https://pandas.pydata.org) `DataFrames`/`Series` and [pickle-based serialization](https://docs.python.org/3/library/pickle.html) for generic Python objects in Jupyter environments.

![GitHub Tag](https://img.shields.io/github/v/tag/rzanetti/jupyter-mimetypes?style=flat&logo=github&label=GitHub&color=888888) ![GitHub License](https://img.shields.io/github/license/rzanetti/jupyter-mimetypes?style=flat&logo=github&label=License&color=888888) ![AUR Version](https://img.shields.io/aur/version/python-jupyter-mimetypes?style=flat&logo=archlinux&label=AUR&color=1793d1) ![AUR License](https://img.shields.io/aur/license/python-jupyter-mimetypes?style=flat&logo=archlinux&label=License&color=1793d1) ![PyPI - Version](https://img.shields.io/pypi/v/jupyter-mimetypes?style=flat&logo=pypi&label=PyPI&color=0073b7) ![Static Badge](https://img.shields.io/badge/BSD--3--Clause-0073b7?style=flat&logo=pypi&label=License)

## Why this package exists?

This repository provides an [Arch Linux](https://archlinux.org) `PKGBUILD` for software that is not currently available in the [official repositories](https://wiki.archlinux.org/title/Official_repositories).

The goal is to make installation reproducible, auditable, and compatible with standard Arch Linux packaging practices.

## Upstream project

This repository **does not** contain the original software! It contains only the Arch Linux packaging files.

The software itself is maintained by the upstream project.

Upstream source code:

- [datalayer/jupyter-mimetypes: 🪐 Jupyter Mimetypes - Enhanced Jupyter representation capabilities through proxy objects](https://github.com/datalayer/jupyter-mimetypes)

[PyPI](https://pypi.org) package:

- [jupyter-mimetypes · PyPI](https://pypi.org/project/jupyter-mimetypes)

## Installation

You can install this package directly from the AUR using your favorite AUR helper:

```bash
yay -S python-jupyter-mimetypes
```

If you prefer to build the package manually, just clone it from AUR:

```bash
git clone https://aur.archlinux.org/python-jupyter-mimetypes.git
cd python-jupyter-mimetypes
makepkg -si
```

## Maintenance

The `PKGBUILD` tracks upstream releases published on [PyPI](https://pypi.org/project/jupyter-mimetypes).

Issues related to the packaged software itself should be reported [upstream](https://github.com/datalayer/jupyter-mimetypes).

Issues related to Arch Linux packaging can be reported in this repository.
